# Credit Risk Classficiation Report

## Overview


Built a linear regression model to identify the creditworthiness of borrowers, using a dataset of historical lending activity from a peer-to-peer lending services company. This data included the loan size, interest rate, borrower's income, debt-to-income ratio, the number of accounts the borrow held, derogatory marks, total debt held, and loan status. That data was split into X's (most of the dataset) and y's (loan status, which is what was ultimately being predicted).

The analysis was done using logistic regression, which had an overall 99% accuracy rate. To increase that accuracy, and specifically improve at predicting high-risk loans, the random over sampler module was used as well.

## Results

* Machine Learning Model 1 (Logistic Regression):
  * Accuracy: 0.99
  * Precision: 100% for healthy loans, 85% for high-risk loans
  * Recall: 99% for healthy loans, 91% for high-risk loans



* Machine Learning Model 2 (Logistic Regression with random over sampler):
  * Accuracy: 0.99
  * Precision: 100% for healthy loans, 84% for high-risk loans
  * Recall: 99% for healthy loans, 99% for high-risk loans

## Summary
Model 2 is slightly less accurate than model 1, however, it has higher and more consistent recall.
