# Loan Approval Prediction using Machine Learning

## Project Overview
This project aims to predict whether a loan application will be approved based on applicant information such as income, credit history, employment status, and loan amount.

The project demonstrates classification techniques used in banking and financial risk analysis.

## Objective
To build a classification model that predicts loan approval status.

## Dataset
Loan Prediction Dataset (Kaggle)

Key features include:
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area
- Employment Status

Target Variable:
Loan_Status (Approved / Not Approved)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

## Project Workflow

### 1. Data Exploration
- Examined dataset structure
- Identified missing values
- Analyzed distribution of features

### 2. Data Preprocessing
- Handled missing values
- Converted categorical variables to numeric
- Addressed class imbalance

### 3. Exploratory Data Analysis
Key analysis included:
- Loan approval rate by gender
- Approval rate by income
- Credit history impact
- Boxplots and correlation matrix

### 4. Model Building
The following classification models were trained:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### 5. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Curve

### Results
Random Forest achieved the highest performance in predicting loan approval outcomes.

## Business Impact
Banks can use this model to:
- Reduce loan default risk
- Improve loan approval decisions
- Automate credit risk assessment

## Author
Nitish Devadiga
