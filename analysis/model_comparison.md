# Model Comparison

## Overview

Three regression models were developed to identify the factors associated with monthly sales. Two simple linear regression models were used to evaluate the impact of individual variables, while one multiple regression model combined several business variables to improve prediction accuracy.

---

## Model Comparison Table

| Model   | Dependent Variable | Independent Variables                                                                                                                    | R²   | Significant Variables                             | Business Usefulness                                                              |
| ------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- | ---- | ------------------------------------------------- | -------------------------------------------------------------------------------- |
| Model 1 | Monthly Sales      | Marketing Spend                                                                                                                          | 0.64 | Marketing Spend                                   | Useful for understanding the impact of advertising expenditure.                  |
| Model 2 | Monthly Sales      | Footfall                                                                                                                                 | 0.72 | Footfall                                          | Useful for evaluating customer traffic and store performance.                    |
| Model 3 | Monthly Sales      | Marketing Spend, Footfall, Inventory Availability, Customer Rating, Average Discount, Region Dummy Variables, Store Type Dummy Variables | 0.83 | Marketing Spend, Footfall, Inventory Availability | Most useful model because it considers multiple business factors simultaneously. |

---

## Interpretation

### Model 1 – Marketing Spend

Marketing spend has a positive relationship with monthly sales. Stores investing more in marketing generally achieved higher sales. However, this model does not consider other important operational factors.

### Model 2 – Footfall

Footfall explains more variation in monthly sales than marketing spend alone. Higher customer traffic generally results in greater sales revenue.

### Model 3 – Multiple Regression

The multiple regression model provides the highest explanatory power with an R² of approximately 0.83. This indicates that around 83% of the variation in monthly sales is explained by the variables included in the model.

Important observations include:

* Marketing spend has a positive effect on sales.
* Higher customer footfall significantly increases monthly sales.
* Better inventory availability improves sales performance.
* Customer rating contributes positively but has a smaller effect.
* Average discount percentage shows a weaker relationship after controlling for other variables.
* Region and store type influence sales, indicating structural differences among stores.

---

## Significant Variables

Variables with strong business importance include:

* Marketing Spend
* Footfall
* Inventory Availability

These variables showed statistically meaningful relationships with monthly sales.

Variables such as customer rating and average discount percentage should be interpreted more cautiously because their statistical significance is weaker after controlling for other predictors.

---

## Business Usefulness

The multiple regression model is recommended for business decision-making because it captures several important drivers of sales simultaneously. It allows management to estimate how changes in marketing investment, customer traffic, and inventory availability may influence sales performance.

---

## Limitations

* Regression identifies association rather than causation.
* External factors such as economic conditions and local competition were not fully captured.
* Seasonal effects and promotional campaigns may influence sales but were not explicitly modeled.
* The model assumes linear relationships among variables.
* Predictions may be less accurate for unusual or extreme stores.

---

## Final Model Selected

The Multiple Linear Regression model was selected because it provides the highest explanatory power, includes the major business drivers, and offers practical insights for strategic decision-making.
