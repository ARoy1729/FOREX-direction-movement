# Forex directional Movement Prediction

**Author** : Ahan Roy

This project implements a machine learning model using **Support Vector Machines (SVM)** to predict the direction of EUR/JPY FOREX price movement based on historical market data.

## Overview

The goal of this project is to classify future FOREX movements using past OHLCV (Open, High, Low, Close, Volume) data. The model predicts whether the price will go **up** or **down** based on engineered features.

## Tools Used

- Python
- pandas, NumPy
- scikit-learn (SVM, GridSearchCV)
- matplotlib, seaborn (for visualization)

## Dataset

- Dataset used: Historical exchange rate data for EUR/JPY
- Features used:
  - Open, High, Low, Close prices
  - Target variable: Direction of movement

## How It Works

1. **Data Loading & Cleaning**
   - Load CSV data and handle missing values.

2. **Feature Engineering**
   - Scale features
   - Create a target column for binary classification (e.g., price up/down)

3. **Model Training**
   - Train a Support Vector Classifier (SVC)
   - Perform hyperparameter tuning

4. **Evaluation**
   - Accuracy score
   - Classification report
   - Confusion matrix heatmap

## Output

- Accuracy and classification metrics
- Visualizations of model performance
- Insights into how well the SVM classifier predicts forex movement
