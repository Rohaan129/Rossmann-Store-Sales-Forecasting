# Rossmann Store Sales Forecasting

## Project Overview

This project predicts daily sales for Rossmann stores using historical sales data, store information, promotions, and holiday features. The goal is to build a machine learning model that can accurately forecast future store sales.

## Dataset

Source: Kaggle Rossmann Store Sales Competition

Files used:

- train.csv
- test.csv
- store.csv
- sample_submission.csv

## Problem Statement

Rossmann operates over 3,000 drug stores across Europe. Store managers can influence sales through promotions, pricing, and inventory planning. This project aims to predict daily sales for each store using historical sales and store-related features.

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Hyperparameter Tuning
8. Model Evaluation
9. Sales Prediction

## Feature Engineering

The following features were created from the Date column:

- Day
- Month
- Year
- Month End
- Quarter End

Additional store-related features include:

- Store Type
- Assortment
- Promo
- School Holiday
- State Holiday
- Competition Distance

## Data Preprocessing

- Missing value imputation using SimpleImputer
- One-Hot Encoding for categorical variables
- Min-Max Scaling for numerical features

## Models Used

### Baseline Model

Predicts the mean sales value for all records.

### Decision Tree Regressor

Used to capture non-linear relationships in the data.

### Random Forest Regressor

Ensemble learning model that combines multiple decision trees for improved prediction performance.

## Evaluation Metric

The model performance was evaluated using RMSE (Root Mean Squared Error).

RMSE measures the average prediction error between actual sales and predicted sales. Lower RMSE indicates better performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Rossmann-Store-Sales-Forecasting/
│
├── train.csv
├── test.csv
├── store.csv
├── sample_submission.csv
│
├── Rossmann_Sales_Forecasting.ipynb
├── README.md
├── requirements.txt
└── app.py
```

## Future Improvements

- XGBoost Regressor
- LightGBM Regressor
- Advanced Feature Engineering
- Streamlit Web Application Deployment

## Author

**Rohaan Farooq**

GitHub: https://github.com/Rohaan129