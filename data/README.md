# Data
-   **[Credit Card Dataset]**: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata 

# Codebook for [chosen] Dataset

## Variable Names and Descriptions:

- **CUST_ID**: Identification of Credit Card holder
- **BALANCE**: Balance amount left in their account to make purchases
- **BALANCE_FREQUENCY**: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- **PURCHASES**: Amount of purchases made from account
- **ONEOFF_PURCHASES**: Maximum purchase amount done in one-go
- **INSTALLMENTS_PURCHASES**: Amount of purchase done in installment
- **CASH_ADVANCE**: Cash in advance given by the user
- **PURCHASES_FREQUENCY**: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- **ONEOFFPURCHASESFREQUENCY**: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- **PURCHASESINSTALLMENTSFREQUENCY**: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- **CASHADVANCEFREQUENCY**: How frequently the cash in advance is being paid
- **CASHADVANCETRX**: Number of Transactions made with "Cash in Advanced"
- **PURCHASES_TRX**: Number of purchase transactions made
- **CREDIT_LIMIT**: Limit of Credit Card for user
- **PAYMENTS**: Amount of Payment done by user
- **MINIMUM_PAYMENTS**: Minimum amount of payments made by user
- **PRCFULLPAYMENT**: Percent of full payment paid by user
- **TENURE**: Tenure of credit card service for user

## Data Types:

- **CUST_ID**: String (Categorical)
- **BALANCE**: Float (Continuous)
- **BALANCE_FREQUENCY**: Float (Continuous, range 0-1)
- **PURCHASES**: Float (Continuous)
- **ONEOFF_PURCHASES**: Float (Continuous)
- **INSTALLMENTS_PURCHASES**: Float (Continuous)
- **CASH_ADVANCE**: Float (Continuous)
- **PURCHASES_FREQUENCY**: Float (Continuous, range 0-1)
- **ONEOFF_PURCHASES_FREQUENCY**: Float (Continuous, range 0-1)
- **PURCHASES_INSTALLMENTS_FREQUENCY**: Float (Continuous, range 0-1)
- **CASH_ADVANCE_FREQUENCY**: Float (Continuous, range 0-1)
- **CASH_ADVANCE_TRX**: Integer (Discrete)
- **PURCHASES_TRX**: Integer (Discrete)
- **CREDIT_LIMIT**: Integer (Discrete)
- **PAYMENTS**: Float (Continuous)
- **MINIMUM_PAYMENTS**: Float (Continuous)
- **PRC_FULL_PAYMENT**: Float (Continuous, range 0-1)
- **TENURE**: Integer (Discrete)


