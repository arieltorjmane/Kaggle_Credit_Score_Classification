# FML Kaggle Challenge: Credit Score Classification

## Overview
Welcome to the high-stakes world of Global Finance Inc., where you have assumed the role of the lead data scientist. 
Your company, with its vast expanse of banking and financial services, has amassed a considerable amount of data, ranging from basic banking details to intricate credit histories of clients who span the globe.

## Description

### Business Challenge:
The top brass (your management) has laid down a strategic initiative: to streamline the credit assessment process. They envisage an automated system that can swiftly and accurately categorize clients into distinct credit score brackets, thereby enhancing the efficiency of the credit evaluation process and enabling more informed decision-making.

### Your Objective:
Your task is to develop a sophisticated machine-learning model that leverages the wealth of credit-related information at your disposal to classify clients into appropriate credit score brackets. This system should serve as a robust analytical tool that aids in the accurate assessment of credit risks and the allocation of credit scores.

Get ready to dive into the data, draw insights, and deploy your model—the future of credit scoring at Global Finance Inc. rests in your capable hands. Let the challenge commence!

### Info:
As part of our credit score classification challenge, we have at our disposal a dataset that serves as a financial footprint of our customers. This dataset includes a comprehensive set of variables:

Variable :	Description

ID :	Unique identifier for the record

Customer_ID	: Unique identifier for the customer

Month :	Month when the data was recorded

Name :	Name of the customer

Age :	Age of the customer

SSN :	Social Security Number of the customer

Occupation :	Customer's occupation

Annual_Income :	Customer's yearly income

Monthly_Inhand_Salary	: Customer's take-home salary per month

Num_Bank_Accounts :	Number of bank accounts the customer holds

Num_Credit_Card :	Number of credit cards the customer has

Interest_Rate :	Interest rate applicable to the customer

Num_of_Loan :	Number of loans associated with the customer

Type_of_Loan :	Types of loans the customer has

Delay_from_due_date :	Days past due date for payments

Num_of_Delayed_Payment :	Number of times payments have been delayed

Changed_Credit_Limit :	Any changes in the credit limit

Num_Credit_Inquiries :	Number of credit-related inquiries

Credit_Mix :	Diversity of credit types the customer has

Outstanding_Debt :	Total debt outstanding

Credit_Utilization_Ratio :	Ratio of used credit to available credit

Credit_History_Age :	Age of the customer's credit history

Payment_of_Min_Amount :	Indicator of minimum payment made or not

Total_EMI_per_month :	Total Equated Monthly Installments paid per month

Amount_invested_monthly :	Monthly investment amount

Payment_Behaviour :	Customer's payment habits

Monthly_Balance :	Balance amount each month

Credit_Score :	Customer's credit score


## Dataset Description

Files
train_set.csv - the training set with the label to predict 'Credit_Score'
test_set.csv - the test set without the label to predict 'Credit_Score'. This is the set you will need to submit in your solution for the leaderboard>

## Download Data
Visit this page for Kaggle API: 
https://github.com/Kaggle/kaggle-api

Use this command to download the data
kaggle competitions download -c fml-kaggle-challenge-credit-score-classification

## Evaluation

The evaluation section describes how submissions will be scored and how participants should format their submissions. 
You don't need a sub-title at the top; the page title appears above. Below is an example of a typical evaluation page.

Submissions are evaluated on Accuracy Score between the predicted probability and the observed target.

## Submission File

For each ID in the test set, you must predict a probability for the TARGET variable. The file should contain a header and have the following format:

ID,TARGET
2,Standard
5,Poor
6,Good
etc.
