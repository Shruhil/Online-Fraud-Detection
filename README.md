# Online-Fraud-Detection
# Overview
This project involves developing a machine learning model to detect fraudulent transactions in an online payment dataset. The dataset used contains various features of transactions, such as transaction amount, account balances, and transaction types. The main objective is to classify transactions as fraudulent or non-fraudulent accurately.
# Dataset Information
The dataset used in this project is available from Kaggle: Online Payment Fraud Detection. The dataset contains details of online transactions and has features that can be used to identify fraudulent activities.

# Features:

* step: Time step of the transaction<br />
* type: Type of transaction (e.g., PAYMENT, CASH_IN) <br />
* amount: Amount of the transaction <br />
* nameOrig: Customer identifier <br />
* oldbalanceOrg: Initial balance of the customer <br />
* newbalanceOrig: New balance of the customer <br />
* nameDest: Recipient identifier <br />
* oldbalanceDest: Initial balance of the recipient <br />
* newbalanceDest: New balance of the recipient <br />
* isFraud: Label indicating if the transaction is fraudulent (1) or not (0) <br />


# Why this Project
Importance of Online Payment Fraud Detection
* Online payment fraud is a significant concern in digital transactions, impacting financial institutions, businesses, and consumers alike. Detecting fraudulent transactions is crucial for:

* Minimizing Financial Losses: Fraudulent transactions can lead to substantial financial losses for businesses and individuals.

* Protecting Customers: Ensuring the security of customers' financial assets and personal information.* 

* Maintaining Trust: Upholding trust and confidence in digital payment systems and financial institutions.

# Python Libraries
pandas, numpy, seaborn, matplotlib, tabulate, sklearn

Random Forest and Naive Bayes were used to identify online payment fraud due to the large dataset.

# Results
The final model (Random Forest Classifier) achieves robust performance in detecting fraudulent transactions, as shown by evaluation metrics and visualizations.
