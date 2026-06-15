# FraudShield By Tamil Selvan D

Tool: Python, Jupyter Notebook

Dataset: Credit Card Fraud Detection Dataset (Kaggle)
Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?

## Project Description
- FraudShield is a Machine Learning project developed using the Gaussian Naive Bayes algorithm to detect fraudulent credit card     transactions.
- The system analyzes transaction-related features and predicts whether a transaction is legitimate or fraudulent.

## Features Used
* Time
* Amount
* V1
* V2
* V3

## Target Variable
* Class
  * 0 = Legitimate Transaction
  * 1 = Fraudulent Transaction

## Data Cleaning
* Checked missing values
* Removed 1081 duplicate records
* Prepared data for model training

## Algorithm Used
* Gaussian Naive Bayes

## Key Results
Accuracy Score: 99.12%

Confusion Matrix:
[[281086 2167]
[341 132]]

## Sample Prediction
Input:
* Time = 1000
* Amount = 150
* V1 = -1.2
* V2 = 0.5
* V3 = 1.1

Output:
Legitimate Transaction

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Outcome
Developed a fraud detection system capable of identifying suspicious credit card transactions using machine learning techniques. The project demonstrates the practical application of Gaussian Naive Bayes in financial fraud detection.
