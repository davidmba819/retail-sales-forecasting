# Retail Sales Forecasting Using Machine Learning

## Project Overview

This project focuses on forecasting future retail sales using Walmart sales data. The goal is to analyze historical sales behavior, identify important business patterns, and build machine learning models capable of predicting future weekly sales.

The project combines:

* exploratory data analysis
* retail business analysis
* feature engineering
* machine learning
* forecasting techniques

---

# Business Problem

Retail businesses depend on accurate sales forecasting for:

* inventory planning
* staffing decisions
* promotional strategies
* revenue planning

Poor forecasting may lead to:

* overstocking
* stock shortages
* revenue loss
* operational inefficiencies

This project aims to understand the factors influencing weekly retail sales and develop models capable of forecasting future sales behavior.

---

# Dataset Information

The project uses the Walmart Store Sales Forecasting dataset.

### Datasets Used

* `train.csv` → historical weekly sales
* `features.csv` → economic indicators and markdown data
* `stores.csv` → store metadata

### Main Target Variable

* `Weekly_Sales`

---

# Project Workflow

## Notebook 1 — Data Understanding, Cleaning & EDA

Completed:

* dataset inspection
* dataset merging
* missing value investigation
* duplicate checks
* data cleaning
* target variable analysis
* seasonality analysis
* holiday sales analysis
* store-level analysis
* department-level analysis
* markdown analysis
* economic factor analysis
* time-based sales analysis
* correlation analysis
* EDA summary and conclusions

---

## Notebook 2 — Feature Engineering & Data Preparation

Completed:

* missing value treatment
* time-based feature engineering
* categorical encoding
* lag feature engineering
* rolling window feature engineering
* cyclical time encoding
* forecasting feature generation
* chronological train-test split
* feature scaling
* Yeo-Johnson target transformation
* forecasting dataset preparation

### Forecasting Features Created

* `Lag_1`
* `Lag_4`
* `Rolling_Median_4`
* `Rolling_Std_4`
* `Month_Sin`
* `Month_Cos`
* `WeekOfYear_Sin`
* `WeekOfYear_Cos`

### Final Modeling Datasets

* `X_train`
* `X_test`
* `X_train_scaled`
* `X_test_scaled`
* `y_train`
* `y_test`
* `y_train_log`
* `y_test_log`

---

## Notebook 3 — Modeling & Forecasting

Planned:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest
* XGBoost
* LightGBM
* CatBoost
* Prophet Forecasting
* model evaluation
* model comparison
* hyperparameter tuning
* forecasting visualization
* business insights and recommendations

---

# Key Insights from EDA

* Weekly sales are heavily right-skewed with extreme sales spikes.
* Strong seasonal sales patterns were observed during end-of-year periods.
* Holiday periods contribute to higher sales variability.
* Larger stores generally produce higher sales.
* Store type influences sales behavior.
* Sales vary significantly across departments.
* Markdown activities show weak to moderate relationships with sales.
* Economic indicators show weak direct relationships with weekly sales.
* The dataset contains strong time-based patterns suitable for forecasting.

---

# Feature Engineering Highlights

* Historical lag features were created to capture previous sales behavior.
* Rolling window statistics were generated to model recent sales trends and volatility.
* Cyclical encoding was applied to seasonal variables to preserve circular time relationships.
* A chronological split was used to prevent data leakage during forecasting evaluation.
* Yeo-Johnson transformation was applied to reduce target skewness and stabilize the sales distribution.

---

# Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* LightGBM
* CatBoost
* Prophet

---

# Project Status

Current Phase:

* Feature Engineering & Data Preparation Completed

Next Phase:

* Machine Learning Modeling & Forecasting

---
