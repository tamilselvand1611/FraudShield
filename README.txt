# FraudShield – Credit Card Fraud Detection System

Developed By
Tamil Selvan D

## Tools & Technologies
* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Dataset
Credit Card Fraud Detection Dataset (Kaggle)

Dataset Link:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Project Overview
- FraudShield is a Machine Learning-based credit card fraud detection system developed using the Gaussian Naive Bayes algorithm.
- The system analyzes transaction-related information and predicts whether a transaction is legitimate or fraudulent. To improve usability, technical dataset features were mapped to user-friendly transaction inputs, making the system resemble a real-world banking fraud detection application.

## Problem Statement
- Credit card fraud causes significant financial losses worldwide. Detecting fraudulent transactions quickly and accurately is essential for financial institutions.
- FraudShield helps identify suspicious transactions using machine learning techniques and provides fraud probability along with risk assessment.

## Data Preprocessing
The following preprocessing steps were performed:
* Checked for missing values
* Identified duplicate records
* Removed 1081 duplicate transactions
* Prepared dataset for model training

Dataset Shape After Cleaning:
* Rows: 283726
* Columns: 31

## Features Used For Model Training
Input Features:
* Time
* Amount
* V1
* V2
* V3

Target Feature:
* Class

Class Values:
* 0 → Legitimate Transaction
* 1 → Fraudulent Transaction

## Machine Learning Algorithm
### Gaussian Naive Bayes
- Gaussian Naive Bayes is a probabilistic machine learning algorithm based on Bayes' Theorem.

Why Used:
* Fast and efficient
* Works well with numerical data
* Suitable for binary classification problems
* Easy to implement and interpret

## Model Performance
### Accuracy Score = 99.12%
### Confusion Matrix
[[281086 2167]
[341 132]]

### Performance Summary
* Correctly classified most legitimate transactions
* Successfully detected fraudulent transactions
* Demonstrated high overall classification accuracy

## FraudShield User Interface
- Instead of exposing technical dataset features such as V1, V2, and V3 directly to users, the system uses a user-friendly transaction form.

### User Inputs
* Transaction Amount
* Transaction Time
* Merchant Category
  * Shopping
  * Food
  * Travel
  * Entertainment
  * Online Payment
* Transactions Today
* Customer Type
  * New Customer
  * Existing Customer
These inputs are internally mapped to model features for prediction.

## Fraud Detection Report
The system generates:
* Fraud Prediction
* Fraud Probability (%)
* Risk Level
  * Low
  * Medium
  * High
* Transaction Status
Example:
Fraud Probability: 0.46%
Risk Level: LOW
Status: Transaction Approved

## Data Visualization
FraudShield visualizes model performance using:
* Confusion Matrix Heatmap
* Matplotlib
* Seaborn
This helps evaluate classification performance visually.

## Key Learning Outcomes
Through this project, I gained practical experience in:
* Data Cleaning
* Exploratory Data Analysis
* Machine Learning Model Training
* Gaussian Naive Bayes Classification
* Fraud Detection Systems
* Performance Evaluation
* Data Visualization
* Real-World User Interface Design

## Future Enhancements
* Streamlit Web Application
* Power BI Dashboard Integration
* Additional Machine Learning Algorithms
* Real-Time Transaction Monitoring
* Enhanced Fraud Risk Analysis
* Banking-Style User Interface

## Conclusion
- FraudShield demonstrates the practical application of Machine Learning in financial fraud detection. The project combines data preprocessing, classification, visualization, and user-friendly transaction analysis to provide an effective fraud detection solution.
