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

## Notebook 2 — Feature Engineering & Data Preparation

Planned:

* date feature extraction
* missing value treatment
* categorical encoding
* feature transformation
* train-test split
* scaling
* final modeling dataset preparation

## Notebook 3 — Modeling & Forecasting

Planned:

* regression models
* boosting models
* Prophet forecasting
* model evaluation
* model comparison
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

* Exploratory Data Analysis Completed

Next Phase:

* Feature Engineering and Data Preparation

