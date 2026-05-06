# Project Overview
This project analyzes a dataset of over 400,000 used cars to identify
the key factors influencing vehicle prices. The goal is to provide
actionable insights for used car dealerships to optimize inventory and
pricing strategies. The submission is located at https://github.com/alirezataba/module11 

# Business Objective
Determine what factors make a used car more or less expensive and
support better dealership decisions.

# Dataset

- Source: Kaggle Used Cars Dataset (provided)
- Size: ~426,000 samples
- Features: price, year, odometer, condition, fuel, transmission, type, etc.

# Data Preparation
- Removed invalid values
- Handled missing values
- Removed highly incomplete columns
- Addressed outliers
- Standardized categorical variables

# Modeling
Models used:
- Linear Regression
- Ridge Regression
- Lasso Regression

Final model picked: Ridge Regression

# Model Performance
- RMSE: ~0.57 (log scale)
- R²: ~0.65
- Strong generalization (CV ≈ Test)

# Key Insights
- Condition strongly impacts price
- Newer cars are more valuable
- Higher mileage reduces price
- Diesel vehicles show higher value
- Pickup trucks command higher prices

# Business Recommendations
- Focus on newer, low-mileage vehicles
- Prioritize good/excellent condition
- Stock more pickup trucks
- Avoid low-condition, high-mileage cars

# Limitations
- Model explains ~65% of variance
- Missing external factors (market, history)

# Future Work
- Add external data
- Improve feature engineering
- Test additional models

# Key Takeaway
Used car prices are primarily driven by condition, age, mileage, and vehicle type.
