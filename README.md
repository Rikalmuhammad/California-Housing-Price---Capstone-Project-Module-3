# California-Housing-Price---Capstone-Project-Module-3
A machine learning project using 1990s California housing data to predict median house values. Built for educational purposes, this project demonstrates end-to-end regression modeling, feature engineering, and evaluation to support real estate and urban planning insights.

## Business Problem Understanding

### Context

Accurately predicting housing prices in California is a valuable task for various stakeholders such as buyers, real estate investors, urban planners, and financial institutions. House prices are influenced by numerous interrelated factors including location, population characteristics, income levels, and proximity to natural or urban features.

### Objective

The goal of this project is to develop a robust and interpretable machine learning model that can predict the median house value in California housing blocks based on a combination of geographic, demographic, and economic features.

### Approach Summary

To achieve this, we performed:

- **Comprehensive Data Cleaning**: Handled outliers, capped data, and logical inconsistencies.
- **Feature Engineering**: Created domain-relevant features such as `room_per_households`, `income_per_person`, and `bedroom_ratio`.
- **Exploratory Data Analysis (EDA)**: Identified key patterns, distributions, and potential data issues.
- **Model Comparison**: Tested and compared several models including Linear Regression, Ridge, Lasso, Random Forest, and HistGradientBoostingRegressor.
- **Final Model**: HistGradientBoostingRegressor was selected based on cross-validation and test set performance.

### Why HistGradientBoosting?

Initially, XGBoost was considered, but HistGradientBoostingRegressor was selected as the final model because:
- It showed better performance in both accuracy and generalization.
- It natively handles missing values and is highly efficient for medium-to-large datasets.
- It supports full integration with `scikit-learn` pipelines, including preprocessing steps.

### Expected Impact

A well-performing prediction model enables:
- **Better pricing strategy** for real estate listings
- **Smarter investment decisions** based on regional housing trends
- **Support for policy planning** in affordable housing and urban development
