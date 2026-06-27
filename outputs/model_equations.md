# Model Equations

## Simple Regression Model 1

Dependent Variable:

Monthly Sales

Independent Variable:

Marketing Spend

Regression Equation:

**Monthly Sales = β₀ + β₁ × Marketing Spend**

### Interpretation

* β₀ represents the estimated sales when marketing spend is zero.
* β₁ represents the expected increase in monthly sales for every one-unit increase in marketing spend.

Marketing spend showed a positive relationship with monthly sales.

---

## Simple Regression Model 2

Dependent Variable:

Monthly Sales

Independent Variable:

Footfall

Regression Equation:

**Monthly Sales = β₀ + β₁ × Footfall**

### Interpretation

* β₀ represents baseline sales.
* β₁ represents the increase in sales associated with each additional customer visiting the store.

Footfall demonstrated a strong positive relationship with sales.

---

## Multiple Regression Model

Dependent Variable:

Monthly Sales

Regression Equation:

**Monthly Sales = β₀ + β₁(Marketing Spend) + β₂(Footfall) + β₃(Inventory Availability) + β₄(Customer Rating) + β₅(Average Discount) + β₆(Store Type Dummy) + β₇(Region Dummy)**

---

## Coefficient Interpretation

### Marketing Spend

Positive coefficient indicating that higher marketing expenditure is associated with higher monthly sales.

### Footfall

Positive coefficient indicating that stores with greater customer traffic generally achieve higher sales.

### Inventory Availability

Positive coefficient indicating that maintaining inventory availability supports higher revenue.

### Customer Rating

Positive coefficient suggesting better customer experience contributes to increased sales.

### Average Discount Percentage

Represents the relationship between discounting strategy and sales after controlling for other variables.

### Dummy Variables

Dummy variables capture differences among categorical groups while holding other variables constant.

---

## Dummy Variable Approach

Categorical variables converted into dummy variables:

* Region
* Store Type

### Reference Categories

Region Reference Category:

**North**

Store Type Reference Category:

**Supermarket**

The reference categories were excluded from the regression model to avoid multicollinearity (Dummy Variable Trap).

---

## Final Model Selected

Multiple Linear Regression

### Reason for Selection

* Highest R² value (approximately 0.83)
* Includes multiple business drivers simultaneously
* Better prediction accuracy
* Provides stronger support for business decision-making than simple regression models
