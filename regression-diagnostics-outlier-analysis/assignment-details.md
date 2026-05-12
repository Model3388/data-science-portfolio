# Regression Diagnostics and Outlier Analysis

## Overview

This project evaluates a multiple linear regression model used to determine mortgage points offered to clients. The focus is on identifying potential violations in the model and assessing the impact of outliers.

## Scenario

A real estate financing company developed a regression model using:

* Closing costs
* Inflation rate

to predict mortgage points offered to clients.

## Observations

The model reported an R² of approximately 39.35%, indicating moderate explanatory power. However, visual inspection of scatter plots revealed a significant outlier in the inflation rate variable.

## Outlier Identification

One data point was observed at:

* Approximately 7% inflation
* Approximately 3.25 mortgage points

This value is far removed from the main cluster of observations, which lie between 2% and 4% inflation.

## Impact on the Model

The presence of this outlier may:

* Distort regression coefficients
* Misrepresent relationships between variables
* Reduce model reliability

## Proposed Solution

Instead of immediately removing the outlier, the following steps are recommended:

1. Verify the accuracy of the data point
2. Re-examine the data collection process
3. Re-run the regression model
4. Validate calculations such as residuals and R²

If the outlier is confirmed to be erroneous, it may then be excluded or adjusted appropriately.

## Conclusion

This project highlights the importance of regression diagnostics in data analysis. Identifying and addressing outliers ensures that models produce reliable and meaningful results for business decision-making.
