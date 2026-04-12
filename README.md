# 🏠 House Price Prediction Using Regression

A regression-based machine learning project that predicts house prices from structured housing data using statistical and machine learning techniques.

---

## Overview

This repository demonstrates an end-to-end workflow for a house price prediction system, including data preprocessing, feature engineering, model training, and evaluation.

The project is designed with a focus on clean implementation, reproducibility, and alignment with industry-level practices.

---

## Problem Statement

Given structured housing features, predict the corresponding house price as a continuous numerical value.

---

## Solution Approach

- Load and explore the housing dataset  
- Perform data cleaning and preprocessing  
- Engineer relevant features (e.g., house age)  
- Split data into training and testing sets (80:20)  
- Train a regression model on training data  
- Evaluate model performance on unseen test data  

---

## Model Details

- **Problem Type:** Supervised Regression  
- **Model:** Ordinary Least Squares (OLS) Linear Regression  
- **Target Variable:** House Price (continuous)  
- **Evaluation Metrics:** R² Score, Error Metrics  

This model serves as a baseline and can be extended using advanced regression techniques.

---

## Technology Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Statsmodels  
- Scikit-learn  

---

## Dataset

- **Type:** Structured tabular dataset  
- **Features:** Numerical attributes related to housing characteristics  
- **Target:** House Price  

---

## Results

The regression model successfully captures the relationship between input features and house prices, achieving strong predictive performance on test data.

---

## Model Performance

- R² Score (Train): ~0.999  
- R² Score (Test): ~0.998  

---

## Repository Structure
house-price-prediction-regression/
│
├── House_Price_Prediction_Regression.ipynb
├── README.md
├── requirements.txt
└── LICENSE
---

## Future Improvements

- Address multicollinearity between features  
- Apply regularized models (Ridge, Lasso)  
- Perform residual analysis  
- Deploy as a web application (Streamlit)  

---

## Author

Ayush Kumar Chaubey
