
# ReCell – Used Mobile Phone & Tablet Price Prediction

## Project Overview
This project analyzes the used and refurbished mobile phone and tablet market to identify the key factors influencing resale prices.

The objective is to help ReCell, a used-device marketplace startup, understand pricing trends and develop a machine learning model to predict the normalized resale price of devices.

## Business Objective
- Identify the key factors affecting used-device prices.
- Explore relationships between device specifications and resale value.
- Develop a Linear Regression model to predict used-device prices.
- Provide actionable insights to support pricing strategies.

## Dataset
- 3,454 device records
- 15 attributes
- Device specifications, brand, operating system, usage, and pricing information
- Target variable: `normalized_used_price`

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Statsmodels
- Exploratory Data Analysis
- Linear Regression

## Analysis & Methodology
1. Data loading and exploratory data analysis
2. Missing-value treatment
3. Feature engineering
4. Outlier analysis
5. Categorical feature encoding
6. Correlation and multicollinearity analysis
7. Linear Regression model development
8. Model evaluation and regression assumption checks

## Key Findings
- Normalized new-device price has the strongest positive correlation with used-device price.
- Screen size, battery capacity, camera specifications, and RAM are positively associated with resale value.
- Longer device usage is negatively associated with resale price.
- Android devices account for approximately 93.05% of the devices in this dataset.

## Model Performance

| Metric | Test Result |
|---|---:|
| Adjusted R² | 0.844 |
| RMSE | 0.228 |
| MAE | 0.178 |
| MAPE | 4.24% |

The final Linear Regression model explains approximately 84% of the variation in normalized used-device prices.

## Business Recommendations
- Consider original device price and key specifications when developing resale pricing strategies.
- Account for device age and usage when estimating resale value.
- Monitor brand-specific pricing patterns and device features.
- Periodically update the model with newer market data.

## Project Files
- `recell_used_device_price_prediction.ipynb` – Google Colab containing the complete analysis and modeling workflow.

## Author
Swati Verma

Data Analytics | Python | SQL | Machine Learning
