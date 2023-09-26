# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to identify high-risk loans based on other financial data available. The data included loan size, interest rate, income, debt to income ratio, number of accounts, derogatory marks and total debt. The model is designed to predict which of two categories a loan can be classified into: healthy, or high-risk. The predictions were made using a logistic regression model.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model:
  * Accuracy: 99%
  * Precision: 100% for healthy, 85% for high-risk 
  * Recall: 99% for healthy, 91% for high-risk.

## Summary

I would not recommend this model due to it's 91% recall rate for high-risk loans. This indicates a false-negative rate of 9%, which in my opinion is too high to be useful. The model is missing 9% of the loans that need to be flagged. This model is better at identifying healthy loans, but this information is not as valuable as identifying high-risk loans. If a loaning institution knows which loans are high-risk, they can take steps to mitigate their risk. I would recommend trying to create a model with higher recall for the high-risk loans.

