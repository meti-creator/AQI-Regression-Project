# AQI Prediction Using Regression

This project predicts the Air Quality Index (AQI) using machine learning regression techniques.

## 📌 Problem Statement
Air quality is influenced by multiple environmental factors. The goal of this project is to build a regression model that accurately predicts AQI values based on pollutant concentrations.

## 📊 Dataset
- Indian Cities AQI Dataset
- Source: Mendeley
- Preprocessed to handle missing values and scaling

## ⚙️ Methodology
- Data cleaning and preprocessing
- Feature scaling and imputation
- Polynomial feature expansion
- SGD Regressor with L2 regularization
- Train–test split and cross-validation

## 📈 Results
- Test RMSE: ~16 AQI units
- Cross-validation R²: ~0.81
- Baseline RMSE: ~90 AQI units

## 🧠 Key Takeaways
- Polynomial regression significantly improved performance
- Regularization helped control overfitting
- Model generalizes well to unseen data

## 🚀 How to Run
```bash
pip install -r requirements.txt
 
