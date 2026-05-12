# 📊 Regression Diagnostics: Outlier Detection and Model Reliability

## 📌 Overview

This project evaluates the reliability of a multiple linear regression model by analyzing scatter plots and identifying outliers that may distort results. It demonstrates how model diagnostics are critical for ensuring accurate and trustworthy predictions.

## 🧠 Problem Statement

A real estate financing company is determining how many mortgage points to offer clients based on:

* Closing costs
* Inflation rate

A regression model was developed, but concerns arose regarding the validity of the results.

## 📊 Approach

The analysis focused on:

* Reviewing regression output (R² and coefficients)
* Interpreting scatter plots of variables
* Identifying potential violations in model assumptions

## ⚠️ Key Issue Identified

An outlier was observed in the inflation rate scatter plot:

* Around ~7% inflation
* Corresponding to ~3.25 mortgage points

This observation lies far outside the main cluster (2–4% inflation range).

## 📉 Impact on the Model

* Distorts the relationship between variables
* Potentially inflates or misrepresents model fit (R² ≈ 39.35%)
* Reduces confidence in model reliability

## 💡 Proposed Solution

Rather than immediately removing the outlier:

1. Re-examine the original dataset
2. Verify data accuracy and collection methods
3. Re-run the regression model
4. Validate calculations (residuals, variance, R²)

Only after validation should decisions about removing or adjusting the outlier be made.

## 🧠 Key Insight

Outliers can significantly impact regression models. Proper data validation and diagnostic analysis are essential before making business decisions based on model outputs.

## 🛠️ Skills Demonstrated

* Regression diagnostics
* Outlier detection and interpretation
* Model validation
* Translating statistical issues into business implications

## 📎 Files

* 📄 Full Write-Up: `assignment-details.md`
