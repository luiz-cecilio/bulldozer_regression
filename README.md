# Bulldozer Price Prediction Model

## 📊 Overview
Time series regression model designed to predict the sale price of bulldozers using historical transaction data. The model leverages temporal features and advanced regression techniques to achieve high accuracy in price predictions.

## 🎯 Key Performance Metrics
After 100 iterations of RandomizedSearchCV:
- Train MAE: 2,953.82
- Validation MAE: 5,951.25
- Train RMSLE: 0.145
- Validation RMSLE: 0.245
- Train R²: 0.959
- Validation R²: 0.882

## 🔍 Features
- Implementation of RandomForestRegressor with RandomizedSearchCV optimization
- Comprehensive temporal feature engineering
- Time series data preprocessing pipeline
- Robust model evaluation using multiple metrics
- Feature importance analysis
- Time-based cross-validation strategy

## 🛠️ Technologies Used
- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Seaborn/Matplotlib/Plotly for visualization

## 📈 Key Features & Preprocessing

Temporal feature engineering:

Sale date decomposition (year, month, day)
Age of equipment calculation
Time-based aggregations


Handling of missing values
Encoding of categorical variables
Feature scaling and normalization

## 📊 Model Development

Algorithm: RandomForestRegressor
Hyperparameter optimization:

100 iterations of RandomizedSearchCV
Time-series aware cross-validation


Feature importance analysis
Error analysis and validation

## 🔗 Dataset
The dataset includes various features such as:

Sale date
Machine specifications
Usage history
Configuration details
Previous sale information

