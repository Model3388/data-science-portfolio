# Assignment: Explaining Risk Management

## Overview

This project explores how risk pooling and statistical modeling can be used to manage uncertainty in inventory planning.

## Scenario

A corporation operates 12 retail stores with shared inventory that can be transferred between locations. The company is preparing for a high-demand weekend but currently holds only 9,500 units in total inventory.

The goal is to determine how much inventory is required to achieve a **95% fill rate**, ensuring that 95% of customer demand is satisfied.

## Methodology

Demand was modeled using a normal distribution based on prior analysis:

* Mean demand per store: 800 units
* Standard deviation per store: 250 units
* Number of stores: 12

The total demand distribution was calculated by:

* Scaling the mean by the number of stores
* Scaling the standard deviation accordingly

The **percent point function (PPF)** was used to estimate the inventory level required to meet the 95% service level.

## Results

The analysis determined that:

* Required inventory: 11,204 units
* Current inventory: 9,500 units

This indicates a shortfall and the need to increase inventory before the high-demand period.

## Implementation

The analysis was conducted using Python in Google Colab:

* A normal distribution was constructed using mean and standard deviation
* Visualization techniques were used to illustrate demand distribution
* The 95th percentile was identified as the required inventory threshold

## Conclusion

This project demonstrates how statistical modeling improves decision-making under uncertainty. By accounting for variability in demand, businesses can better plan inventory and avoid stockouts during peak periods.
