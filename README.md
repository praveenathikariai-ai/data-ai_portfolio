Credit Card Fraud Detection
Overview
This project develops a machine-learning classification workflow to identify potentially fraudulent credit-card transactions.

The notebook explores transaction data, analyses class imbalance, prepares the features, trains classification models, and evaluates their ability to distinguish legitimate transactions from fraudulent ones.

The project was developed and executed in Google Colab using Python.

Project objective
The objective is to build a fraud-detection model that can identify suspicious transactions while limiting false alarms on legitimate transactions.

Fraud detection is an imbalanced classification problem. In this type of problem, accuracy alone is not sufficient. The project therefore focuses on precision, recall, F1-score, ROC-AUC, and the confusion matrix.

Dataset
The notebook contains a dataset with 11,959 rows and 31 columns.

The columns include:

Time: Time elapsed from the first transaction in the dataset.

V1 to V28: Anonymised numerical features.

Amount: Transaction amount.

Class: Target variable, where 0 represents a legitimate transaction and 1 represents a fraudulent transaction.

The dataset is anonymised. The original feature meanings are not available, so the project focuses on modelling and evaluation rather than business interpretation of individual V features.
