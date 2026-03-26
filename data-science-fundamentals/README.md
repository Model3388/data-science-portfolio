# 📊 Data Science Fundamentals: Simpson’s Paradox in Loan Decision-Making

## 📌 Overview

This project demonstrates how misleading conclusions can arise from aggregated data, using a real-world-inspired financial scenario to illustrate **Simpson’s Paradox**.

## 🧠 Problem Statement

A bank analyzed survey data to determine which corporate loan products were most popular among clients:

* 2-year loans
* 5-year loans
* 10-year loans

Survey results showed:

* 10-year loans: 80% favorability
* 5-year loans: 60% favorability
* 2-year loans: 50% favorability

Based on this, the bank decided to promote 10-year loans.

## ⚠️ Key Insight (Simpson’s Paradox)

When examining actual loan ownership:

* 75 companies held 2-year loans
* 15 held 5-year loans
* 10 held 10-year loans

Although 10-year loans had the highest favorability, they were the **least commonly held**.

This reveals a classic case of **Simpson’s Paradox**, where aggregated percentages obscure the true underlying distribution.

## ❌ Flawed Decision

The bank increased promotion of 10-year loans based solely on favorability percentages, ignoring:

* actual usage patterns
* distribution of loan ownership

## 💡 Proposed Solution

A more effective strategy would incorporate both preference and usage data.

Proposed pricing model:

* 2-year loans → higher cost (high demand)
* 5-year loans → moderate cost
* 10-year loans → lower cost (low adoption)

This approach aims to better align pricing with demand and encourage balanced loan distribution.

## 🛠️ Tools Used

* Python
* Jupyter Notebook

## 📎 Files

* 📓 Notebook: `notebook.ipynb`
* 📄 Full Write-Up: `assignment-details.md`

