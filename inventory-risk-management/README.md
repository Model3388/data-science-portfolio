# 📦 Inventory Risk Management Using Statistical Modeling

## 📌 Overview

This project applies statistical modeling to estimate inventory requirements needed to meet customer demand under uncertainty. It demonstrates how **risk pooling and probabilistic forecasting** can improve inventory planning decisions.

## 🧠 Problem Statement

A company operates 12 retail stores with shared inventory that can be redistributed as needed.

* Current total inventory: 9,500 units
* Goal: Achieve a **95% fill rate** (meet 95% of customer demand)

Initial analysis suggested that existing inventory levels were insufficient to meet expected demand during a high-sales weekend.

## 📊 Approach

To estimate required inventory levels, demand was modeled using a **normal distribution**:

* Mean demand per store: 800 units
* Standard deviation per store: 250 units
* Number of stores: 12

Using statistical methods, the total demand distribution was calculated and the **95th percentile (PPF / inverse CDF)** was used to determine the required inventory level.

## 📈 Key Result

* Required inventory for 95% service level: **11,204 units**
* Current inventory: 9,500 units

👉 Conclusion: Inventory must be increased to meet service goals.

## 💡 Business Insight

This analysis highlights the importance of:

* Accounting for variability in demand
* Using probabilistic models instead of averages alone
* Applying risk pooling across multiple locations

## 🛠️ Tools Used

* Python
* Google Colab
* NumPy / SciPy (statistical modeling)
* Data visualization

## 📎 Files

* 📓 Notebook: `notebook.ipynb`
* 📄 Full Write-Up: `assignment-details.md`

