## **Introduction**
 This notebook was made as part of the final project of Data Science at Rakamin Academy
 
## **Problem Statement**
 
Customer churn is a measure of the number of customers who have stopped using the company's products or services. To measure the customer churn ratio can be calculated by dividing the number of customers lost by the number of customers acquired [(Accurate, 2021)](https://accurate.id/marketing-manajemen/customer-churn/). In 2021, the customer churn rate at Bank Java reached 20.38%. Bank Java then contacted PT. Churn Solution Tbk, a financial consulting company, to identify the factors that led customers to churn from Bank Java.
 
## Goals and Objective
Identify the factors that led customers to churn and using machine learning models to predict the probability of customer churn.
 
## **Dataset Information**
 
The dataset from [(Kaggle)](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers) contains information from all customers who were churn from the Bank.
This data contains 14 columns and 10000 rows where each column includes:

*   **RowNumber** : Number listed on each row
*   **CustomerId** : ID number for each customer
*   **Surname** : Family/last name for each customer
*   **CreditScore** : Number of credit scores owned by customers
*   **Geography** : Location of customer addresses by country
*   **Gender** : Customer gender information (Male/Female)
*   **Age** : Information on the age of each customer
*   **Tenure** : Number of customer tenors at Bank Java by year
*   **HasCrCard** : Customers who have a Bank Java credit card (0 = No, 1 = Yes)
*   **EstimatedSalary** : Estimated salary value of each customer
*   **IsActiveMember** : Customer who is active or not (0 = Inactive, 1 = Active)
*   **Exited** : Customer who are churn or not (0 = Not Churn, 1 = Churn)
