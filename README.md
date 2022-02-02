# Customer-default-prediction-on-Portuguese-Bank-Dataset
The main objective is to increase overall customer LTVs by downgrading risky customers  by identifying which customers are likely to default under the traditional credit card plan and should be downgraded to the balance management card.
## Problem Statement:
A financial partner’s primary product is a high-value credit card associated with high customer lifetime values (LTVs). The partner is looking to reduce losses from customer defaults by offering a new, lower-value card that supports balance management and helps customers avoid default.
The main objective is to increase overall customer LTVs by downgrading risky customers to the new balance management card while keeping good
customers in the high-LTV traditional card. You are tasked with identifying which
customers are likely to default under the traditional credit card plan and should be
downgraded to the balance management card.

## Data Description:
These data consist of attributes about 30,000 traditional credit card customers and their credit card billing and payment history from April to September. Additionally, their default status in October is given. For assessment purposes, these data have been partitioned into 2 sets: - train.csv - test.csv
train.csv includes 80% of the original data with labels. test.csv contains 20% of the
original data without labels. You will use test.csv to make predictions for submission.	

## Codebook: 
• limit_bal: Amount of the given credit in dollars: it includes both the individual
consumer credit and his/her family (supplementary) credit.
• sex: Gender (1 = male; 2 = female).
• education: Education (1 = graduate school; 2 = university; 3 = high school; 4 =
others).
• marriage: Marital status (1 = married; 2 = single; 3 = others).
• age: Age (year).
• pay_1:pay_6: History of past payment. We tracked the past monthly payment
records (from April to September) as follows: pay_1 = the repayment status in
September; pay_2 = the repayment status in August; . . .;pay_6 = the repayment
status in April. The measurement scale for the repayment status is: -1 = pay duly;
1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 =
payment delay for eight months; 9 = payment delay for nine months and above.
• bill_amt1:bill_amt6: Amount of bill statement in dollars. bill_amt1 = amount of
bill statement in September; bill_amt2 = amount of bill statement in August; . .
.; bill_amt6 = amount of bill statement in April.
• pay_amt1:pay_amt6: Amount of previous payment in dollars. pay_amt1 = amount
paid in September; pay_amt2 = amount paid in August; . . .; pay_amt6 = amount paid
in April.
• default_oct: response in yes, no of default in October
