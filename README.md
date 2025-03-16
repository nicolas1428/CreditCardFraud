# CreditCardFraud

Credit Card Fraud Detection – Data Collection

Project Overview
This project is part of a capstone focused on gathering and documenting relevant datasets for credit card fraud detection. The goal is to explore, collect, and describe datasets that contain transaction records with fraud labels. These datasets will be used in later stages for further analysis or model development.

Objective
Identify and collect datasets related to credit card fraud detection.
Document dataset sources, descriptions, and features.

Datasets Collected
This project includes three datasets from Kaggle, each providing insights into different aspects of fraudulent transactions. 
These datasets contain both real and synthetic transactions labeled as fraudulent or non-fraudulent.
Each dataset is documented with its source, size, features, and description to ensure clarity and usability for future projects.

Datasets Used

1. Credit Card Fraud Detection Dataset
Source: Kaggle - Credit Card Fraud (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
Size: 284,807 transactions
Description: This dataset contains anonymized credit card transactions from European cardholders. Each transaction is labeled as fraudulent (1) or non-fraudulent (0). It is highly imbalanced, with only 0.172% fraudulent transactions (492 fraud cases).
Features:
Time – Seconds elapsed since the first transaction.
Amount – Transaction amount in Euros.
V1 - V28 – Anonymized numerical features from PCA.
Class – Fraud label (1 = Fraud, 0 = Not Fraud).


2. Fraudulent Transactions Prediction Dataset
Source: Kaggle - Fraudulent Transactions Prediction (https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction)
Size: 590,540 transactions
Description: This dataset contains realistic financial transactions, including customer demographics, transaction details, and fraud indicators. It provides both numerical and categorical features, allowing fraud detection models to consider customer behavior patterns.
Features:
Transaction_ID – Unique identifier for each transaction.
Customer_ID – Unique identifier for the customer.
Age – Age of the customer.
Gender – Gender of the customer.
Amount – Transaction amount.
Merchant – Merchant name.
Category – Type of merchant (Retail, Food, Travel, etc.).
Transaction_Type – Type of transaction (Online, In-Store, ATM, etc.).
Is_Fraud – Fraud indicator (1 = Fraud, 0 = Not Fraud).


3. Credit Card Fraud Dataset
Source: Kaggle - Credit Card Fraud (https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud)
Size: 1,000,000 transactions
Description: This dataset includes both numerical and categorical features, making it more diverse than the first dataset. It contains synthetic credit card transactions with key attributes useful for fraud detection.
Features:
Transaction_ID – Unique transaction identifier.
Time – Timestamp of the transaction.
Amount – Transaction value.
Location – Geographical location of the transaction.
Merchant – Name of the merchant.
Card_Type – Credit card type (Visa, Mastercard, etc.).
Fraud_Label – Fraud indicator (1 = Fraud, 0 = Not Fraud).


Conclusion
This project successfully gathered and documented multiple datasets related to credit card fraud detection. Each dataset was carefully selected to provide a broad understanding of fraudulent transactions, covering different sources, structures, and feature sets.

By focusing solely on data collection and organization, this submission ensures that relevant datasets are easily accessible and well-documented for future use. The provided dataset descriptions offer clear insights into their structure, helping streamline any further analysis or application in fraud detection research.

With this foundation in place, future steps could involve data preprocessing, exploratory analysis, and comparative studies to identify patterns and trends in fraudulent transactions. This submission serves as a structured starting point for deeper investigations into credit card fraud detection.
