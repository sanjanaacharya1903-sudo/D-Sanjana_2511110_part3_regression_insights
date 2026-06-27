# Part 3 – Regression Insights

## Business Problem Summary

A retail chain wants to understand which business factors have the strongest relationship with monthly sales. Management plans to use these insights to optimize marketing budgets, inventory management, staffing, discount strategies, and store operations.

This project applies simple and multiple linear regression to identify variables associated with monthly sales and provide business recommendations.

---

# Dataset Description

Dataset: business_regression_data.xlsx

Number of observations: 320

## Variables

### Dependent Variable

- monthly_sales

### Independent Variables

- marketing_spend
- footfall
- avg_discount_pct
- staff_count
- inventory_availability_pct
- competitor_distance_km
- customer_rating
- holiday_flag
- region
- store_type

---

# Variable Classification

## Numerical Variables

- marketing_spend
- footfall
- avg_discount_pct
- staff_count
- inventory_availability_pct
- competitor_distance_km
- customer_rating
- monthly_profit
- monthly_sales

## Categorical Variables

- region
- store_type

## Binary Variable

- holiday_flag

## Identifier

- store_id

## Date Variable

- month

---

# Variables Excluded from Regression

The following variables were excluded:

- store_id (identifier only)
- month (time reference, not directly used)

---

# Data Preparation

The following preprocessing steps were completed:

- Checked for missing values
- Verified numerical variables
- Created dummy variables for categorical features
- Retained original dataset separately
- Prepared cleaned dataset for regression

---

# Regression Approach

Two Simple Linear Regression models were developed:

1. Monthly Sales vs Marketing Spend
2. Monthly Sales vs Footfall

A Multiple Linear Regression model was also developed using:

- Marketing Spend
- Footfall
- Inventory Availability %
- Customer Rating
- Average Discount %
- Region Dummy Variables
- Store Type Dummy Variables

---

# Dummy Variable Approach

Categorical variables were converted into dummy variables.

Reference categories:

- Region = North
- Store Type = Supermarket

Reference categories were excluded to avoid the Dummy Variable Trap.

---

# Model Comparison Summary

Three regression models were compared using:

- R²
- Adjusted R²
- P-values
- Business interpretability
- Predictive capability

The Multiple Regression model produced the highest explanatory power and was selected as the final model.

---

# Final Model Selected

Multiple Linear Regression

Reason:

- Highest R²
- Better prediction accuracy
- Includes multiple business drivers
- Supports management decision-making

---

# Business Recommendation

The company should prioritize:

- Increasing effective marketing spend
- Improving inventory availability
- Increasing customer footfall
- Monitoring customer satisfaction

Discount strategies should be used carefully because their impact varies across stores.

---

# Assumptions and Limitations

- Regression identifies association, not causation.
- Results depend on data quality.
- External economic conditions are not included.
- Seasonal effects were not modeled.
- Important omitted variables may exist.

---

# Screenshots Included

- simple_regression_output.png
- multiple_regression_output.png
- residuals_preview.png
- model_comparison_preview.png

