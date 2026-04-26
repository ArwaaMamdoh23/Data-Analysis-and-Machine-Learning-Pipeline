# Data Analysis and Machine Learning Pipeline

## Overview
This project is a Jupyter Notebook-based machine learning pipeline that covers end-to-end data processing, exploratory data analysis, feature engineering, and model training using Python.

The goal is to explore the dataset, clean it, and apply machine learning models to extract insights and evaluate performance.

---

## Workflow

### 1. Data Loading
- Load dataset using pandas
- Inspect structure and missing values

### 2. Data Cleaning
- Handle missing values
- Convert categorical variables
- Remove inconsistencies and outliers

### 3. Exploratory Data Analysis (EDA)
- Summary statistics
- Distribution analysis
- Outlier detection using IQR
- Visualizations using matplotlib

### 4. Feature Engineering
- Lag features creation
- Time-based transformations

### 5. Modeling

#### Prophet Model
- Time series forecasting
- Train-test split evaluation
- MAE, MSE, RMSE, MAPE metrics

#### AR Model (AutoReg)
- Time series regression model
- Lag-based prediction
- Evaluation using error metrics

---

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Accuracy (derived from error)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Prophet
- Statsmodels

---

## Results
- Forecasting models applied on time series data
- Comparison between Prophet and AR model performance
- Visualization of predictions vs actual values

---

## Notes
- This project is implemented in a single Jupyter Notebook (`main.ipynb`)
- Focus is on data preprocessing and time series forecasting
