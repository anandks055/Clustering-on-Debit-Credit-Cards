# Clustering-on-Debit-Credit-Cards
Create a clustering model to credit card categorize the dataset into appropriate cluster.
Problem statement: Create a clustering model to credit card categorize the dataset
into appropriate cluster. Context: This case requires to develop a customer
segmentation to define marketing strategy. The
sample Dataset summarizes the usage behavior of about 9000 active credit card
holders during the last 6 months. The file is at a customer level with 18 behavioral
variables.
Column Description:
• CUSTID : Identification of Credit Card holder (Categorical)
• BALANCE : Balance amount left in their account to make purchases
• BALANCEFREQUENCY : How frequently the Balance is updated, score between 0
and 1 (1 = frequently updated, 0 = not frequently updated)
• PURCHASES : Amount of purchases made from account
• ONEOFFPURCHASES : Maximum purchase amount done in one-go
• INSTALLMENTSPURCHASES : Amount of purchase done in installment
• CASHADVANCE : Cash in advance given by the user
• PURCHASESFREQUENCY : How frequently the Purchases are being made, score
between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
• ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in
one-go (1 = frequently purchased, 0 = not frequently purchased)
• PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in
installments are being done (1 = frequently done, 0 = not frequently done)

• CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
• CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
• PURCHASESTRX : Number of purchase transactions made
• CREDITLIMIT : Limit of Credit Card for user
• PAYMENTS : Amount of Payment done by user
• MINIMUM_PAYMENTS : Minimum amount of payments made by user
• PRCFULLPAYMENT : Percent of full payment paid by user
• TENURE : Tenure of credit card service for user
Dataset: https://drive.google.com/file/d/1mvgTrMIolqdrqvF6yxjNyUVpeFziehQ3/view?usp=sharing
Steps to consider:
Read the dataset
Remove/handle null values if any
Perform feature engineering steps (if required)
Standardize the data
Apply PCA to reduce the number of features
Apply K-Means clustering to categorize the dataset
