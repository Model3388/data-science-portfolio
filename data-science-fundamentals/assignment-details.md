# Assignment 1.1: Explaining Potential Errors in Simplified Representations of Data

## Overview

Simpson’s Paradox occurs when a trend observed in aggregated data reverses or disappears when the data is broken into subgroups. This can lead to incorrect conclusions and poor business decisions if not carefully analyzed.

## Scenario

Consider a financial institution analyzing corporate loan preferences. The bank offers three types of loans:

* 2-year loans
* 5-year loans
* 10-year loans

A survey of 100 companies produced the following favorability ratings:

* 10-year loans: 80%
* 5-year loans: 60%
* 2-year loans: 50%

At first glance, this suggests that 10-year loans are the most popular product.

## Underlying Data

However, examining actual loan ownership reveals a different picture:

* 75 companies hold 2-year loans
* 15 companies hold 5-year loans
* 10 companies hold 10-year loans

This indicates that, despite lower favorability, 2-year loans are the most widely used product.

## Interpretation and Error

The bank made a flawed decision by focusing only on aggregated favorability percentages. The **lurking variable** in this case is the number of loans held by companies.

Because the distribution of loan ownership differs significantly from the favorability rankings, the aggregated data provides a misleading picture. This is a clear example of Simpson’s Paradox.

## Business Decision

The bank initially decided to promote 10-year loans more aggressively, based on their high favorability rating. However, this decision ignores actual demand patterns and customer behavior.

## Proposed Solution

As a manager, I would revise this strategy by implementing a pricing model that reflects both demand and adoption rates:

* Increase the cost of 2-year loans due to high demand
* Maintain moderate pricing for 5-year loans
* Reduce the cost of 10-year loans to encourage adoption

This approach aims to balance supply and demand while correcting for the misleading interpretation of aggregated data.

## Conclusion

This example highlights the importance of examining underlying data distributions rather than relying solely on summary statistics. Proper analysis helps prevent flawed decision-making and leads to more effective business strategies.
