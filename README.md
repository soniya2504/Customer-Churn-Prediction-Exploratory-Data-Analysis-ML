# Customer Churn Prediction – Exploratory Data Analysis & ML

## Overview
A polished exploratory data analysis (EDA) and a baseline machine learning model for customer churn prediction. This repository demonstrates the full workflow: data loading, EDA, feature engineering, encoding, feature binning, and a baseline Random Forest model.

## Tech Stack
- Python (pandas, numpy)
- Visualization: matplotlib, seaborn
- Machine Learning: scikit-learn
- Notebook: Jupyter

## Dataset
This project expects a CSV dataset. By default the notebook attempts to load `/mnt/data/Churn_Modelling.csv` (uploaded file) or `churn_data.csv`. The data typically includes customer demographic and account information (e.g., Age, Balance, Tenure, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, and a churn flag like `Exited` or `Churn`).

## Analysis Steps
1. Data loading and initial checks
2. Univariate analysis (distribution and counts)  
3. Bivariate analysis (feature vs churn)
4. Multivariate analysis (correlation heatmap, pairplot)
5. Numerical analysis (skewness, summary stats)
6. Derived features (e.g., `balance_age_ratio`, `active_and_has_card`)
7. Feature binning (age groups) and encoding (Label + One-Hot)
8. Baseline ML models (Random Forest; optional Logistic Regression)

## Results
- Baseline Random Forest accuracy printed in the notebook.
- Feature importance insights from EDA and derived features.
- Visualizations show which segments have higher churn risk (e.g., certain age groups, balances, activity levels).



......................................
.....................................
.....................................
....................................
......................................
