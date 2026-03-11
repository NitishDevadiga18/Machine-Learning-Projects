# House Price Prediction in India using Machine Learning

## Project Overview
This project focuses on predicting house prices in India using machine learning regression models. The model analyzes various property features such as area, number of bedrooms, and location to estimate the expected house price.

The project demonstrates the full data science workflow including data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

## Objective
To build a regression model that accurately predicts housing prices based on key real estate features.

## Dataset
Bangalore Housing Price Dataset (public dataset)

Features include:
- Area (Square Feet)
- Number of Bedrooms (BHK)
- Location
- Bathrooms
- Price

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
- Checked dataset shape and structure
- Identified numerical and categorical variables
- Analyzed missing values

### 2. Data Cleaning
- Removed missing values
- Handled outliers
- Encoded categorical variables

### 3. Exploratory Data Analysis
Performed visual analysis using:
- Correlation heatmap
- Price vs Area analysis
- Price vs BHK analysis
- Location based price distribution
- Boxplots and scatterplots

### 4. Feature Engineering
- Created new feature: price per square foot
- Removed highly skewed or redundant columns

### 5. Model Building
Trained multiple regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 6. Model Evaluation
Models were evaluated using:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

### Results
Random Forest Regression produced the best performance with improved prediction accuracy.

## Business Impact
This model can help:
- Real estate companies estimate property values
- Buyers understand fair market prices
- Developers analyze housing trends

## Author
Nitish Devadiga
