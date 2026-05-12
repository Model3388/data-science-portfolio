# 🏠 Housing Price Prediction Using Multiple Linear Regression

## 📌 Overview

This project demonstrates how multiple linear regression can be used to predict housing prices based on key property features. It focuses on translating statistical model outputs into clear, business-friendly insights.

## 🧠 Problem Statement

A real estate consulting firm seeks to understand which property characteristics most strongly influence housing prices and to build a predictive model for estimating property values.

## 📊 Approach

A **multiple linear regression model (Ordinary Least Squares)** was used to analyze the relationship between housing prices and several key predictors:

* Construction Quality (1–100 scale)
* Living Area (square feet)
* Garage Area (square feet)
* Basement Area (square feet)

## 📈 Key Insights

* Higher construction quality is strongly associated with increased housing prices
* Larger living areas significantly increase property value
* Additional space (garage and basement) contributes positively to price

## 💡 Business Interpretation

The model helps explain how different property features impact pricing:

* Each variable contributes incrementally to the final price
* The model estimates how much price changes when one feature increases, holding others constant
* The selected variables were chosen because they showed the strongest relationship with price

## ❓ Why These Variables?

While other factors (e.g., backyard size, location amenities) may influence price, the model prioritizes variables that:

* Have the strongest statistical relationship with price
* Improve predictive accuracy
* Reduce unnecessary complexity

## ⚠️ Limitations

* Model may omit relevant external factors (e.g., location quality, market conditions)
* Negative intercept is not meaningful in real-world terms
* Assumes linear relationships between variables

## 🛠️ Tools Used

* Python
* Multiple Linear Regression (OLS)
* Statistical analysis

## 📎 Files

* 📄 Full Write-Up: `assignment-details.md`
