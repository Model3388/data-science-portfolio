# 📈 Portfolio Optimization Using Empirical Stock Data

## 📌 Overview

This project analyzes historical stock performance to evaluate risk and return, and to construct a data-driven investment strategy. It demonstrates how empirical data can be used to guide portfolio selection decisions.

## 🧠 Problem Statement

An investor must decide how to allocate capital across three stocks:

* Home Depot (HD)
* Walmart (WMT)
* Amazon (AMZN)

The objective is to evaluate:

* Expected return (mean percentage change)
* Risk (variability in returns)

## 📊 Approach

Historical stock price data over a three-month period (April–July) was analyzed.

For each stock:

* Monthly percentage returns were calculated
* Mean return was used to estimate expected performance
* Variability in returns was used as a proxy for risk

## 📈 Key Findings

* **Amazon (AMZN):**

  * Highest average return (~9.71%)
  * Consistent positive growth across months

* **Home Depot (HD):**

  * Moderate returns (~1.44%)
  * Some variability and negative movement

* **Walmart (WMT):**

  * Lower returns (~1.10%)
  * Relatively stable but limited growth

## 💡 Investment Decision

Based on the analysis, Amazon appears to offer the strongest return profile.

👉 Proposed strategy:

* Allocate a larger portion of the portfolio to Amazon
* Limit exposure to Home Depot and Walmart due to lower returns and variability

## ⚠️ Limitations

* Analysis is based on a short time window (3 months)
* Does not account for broader market conditions
* Assumes past performance reflects future trends

## 🛠️ Tools Used

* Python (Google Colab)
* Basic statistical analysis
* Financial data interpretation

## 📎 Files

* 📄 Full Write-Up: [read](./portfolio-optimization-analysis/assignment-details.md)
