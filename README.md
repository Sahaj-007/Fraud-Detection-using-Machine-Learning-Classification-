# Fraud-Detection-using-Machine-Learning-Classification-
This project focuses on detecting fraudulent financial transactions using Machine Learning classification techniques.The system analyzes transaction data and predicts whether a transaction is fraudulent or legitimate, helping financial institutions reduce losses and improve security.

Features
End-to-end fraud detection pipeline

Data preprocessing and feature engineering

Handling imbalanced dataset

Multiple classification models implementation

Performance evaluation using industry metrics

Dataset Description

The dataset contains transaction-level information with the following features:

Feature Name	Description

step	Time step of the transaction

type	Type of transaction (Transfer, Cash Out, etc.)

amount-Transaction amount

nameOrig-Sender account ID

oldbalanceOrg-Sender balance before transaction

newbalanceOrig-Sender balance after transaction

nameDest-Receiver account ID

oldbalanceDest-Receiver balance before transaction

newbalanceDest-Receiver balance after transaction

isFraud-Target variable (1 = Fraud, 0 = Legitimate)

isFlaggedFraud-Flagged suspicious transactions

Project Workflow
1. Data Collection
Used real-world financial transaction dataset.
2. Data Preprocessing
Handling missing values
Encoding categorical features (transaction type)
Removing irrelevant columns (IDs like nameOrig, nameDest)
Feature scaling if required
3. Exploratory Data Analysis (EDA)
Checked class imbalance
Visualized fraud vs non-fraud transactions
Identified important patterns in transaction behavior
4. Feature Engineering
Created meaningful features using balance differences
Improved model performance using derived features
5. Model Building

Implemented multiple classification algorithms:

Logistic Regression

Decision Tree

Random Forest

6. Handling Imbalanced Data
Used techniques like:

Undersampling / Oversampling

SMOTE (if applied)

Results
Successfully detected fraudulent transactions with high recall

Random Forest provided better performance compared to other models

Model effectively handled class imbalance and reduced false negatives

Sample Output

Transaction Type	Amount	Predicted Result

Transfer	       5000	      Legitimate
Cash Out	      250000	     Fraud



