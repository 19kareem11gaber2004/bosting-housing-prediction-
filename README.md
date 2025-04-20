# bosting-housing-prediction-
Data mining
# Business Understanding

## Problem Statement
A real estate company aims to improve its pricing strategy by developing an accurate house price prediction model. The current process lacks a data-driven approach, leading to potential pricing inefficiencies in the housing market. By leveraging historical housing data, the company wants to establish a reliable method for estimating median home values.

## Objective
Develop a robust regression model to predict `MEDV` (Median Value of owner-occupied homes in $1000s) using various housing features including:
- Crime rate (`CRIM`)
- Number of rooms (`RM`)
- Neighborhood characteristics (`INDUS`, `LSTAT`)
- Property tax rates (`TAX`)
- And other relevant factors

## Success Metrics
The model will be evaluated based on:
- **RMSE (Root Mean Squared Error)**: Target < 3.0 (Lower values indicate better performance)
- **R² Score**: Target > 0.85 (Higher values indicate better explanatory power)

## Data Overview
The dataset contains:
- 506 entries (housing instances)
- 14 features (12 numerical, 2 categorical)
- Target variable: `MEDV` (continuous numerical values ranging from $5k to $50k)

Key observations from preliminary analysis:
- All features have complete data (no missing values)
- Wide ranges in feature values (e.g., crime rate varies from 0.006 to 88.98)
- Potential outliers in maximum values for several features
-
