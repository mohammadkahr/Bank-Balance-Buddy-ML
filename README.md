# Bank-Balance-Buddy-ML
## Credit Prediction Model

This project involves building a regression model to predict the credit limit of bank customers based on various demographic and transactional data provided in the `prediction_credit.csv` file. Below is a detailed description of the data and steps to implement the model.

## Data Description

The dataset contains several features about the customers, categorized into demographic and product variables. Here is the data dictionary for the dataset:

| Column                  | Description                                                |
|-------------------------|------------------------------------------------------------|
| CLIENTNUM               | Client number. Unique identifier for the customer holding the account |
| Customer_Age            | Demographic variable - Customer's age in years             |
| Gender                  | Demographic variable - M=Male, F=Female                    |
| Dependent_count         | Demographic variable - Number of dependents                |
| Education_Level         | Demographic variable - Educational qualification of the account holder |
| Marital_Status          | Demographic variable - Marital status (Married, Single, Divorced, Unknown) |
| Income_Category         | Demographic variable - Annual income category of the account holder |
| Card_Category           | Product variable - Type of card (Blue, Silver, Gold, Platinum) |
| Months_on_book          | Period of relationship with the bank in months             |
| Total_Relationship_count| Total number of products held by the customer              |
| Months_Inactive_12_mon  | Number of months inactive in the last 12 months            |
| Contacts_Count_12_mon   | Number of contacts in the last 12 months                   |
| Credit_Limit            | Credit limit on the credit card                            |
| Total_Revolving_Bal     | Total revolving balance on the credit card                 |
| Total_Amt_Chng_Q4_Q1    | Change in transaction amount (Q4 over Q1)                  |
| Total_Trans_Amt         | Total transaction amount (last 12 months)                  |
| Total_Trans_Ct          | Total transaction count (last 12 months)                   |
| Total_Ct_Chng_Q4_Q1     | Change in transaction count (Q4 over Q1)                   |
| Avg_Utilization_Ratio   | Average card utilization ratio                             |

## Objective

The goal is to predict the `Credit_Limit` of customers using the given features.

## Contact

For any questions or feedback, please reach out to harandi.mohamma@gmail.com.

