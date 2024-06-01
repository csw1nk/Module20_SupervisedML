# Module 12 Report

## Overview of the Analysis

* The purpose of the analysis is to predict the risk of loan default based on financial characteristics.
* The data focused on financial metrics such as loan size, interest rate, borrower income, and others, aiming to predict loan status as either healthy (0) or high-risk (1).
* The variable 'loan_status' had 18,759 healthy loans and 625 high-risk loans.
* The machine learning process included data loading, splitting into training and testing sets, model fitting, and performance evaluation.
* Methods used include LogisticRegression to build the predictive model and performance metrics like confusion matrix and classification report to evaluate it.

## Results

* Machine Learning Model 1:
Accuracy: 100% — The model correctly predicted all instances in the test set.
Precision: 100% — The model perfectly predicted both healthy loans (0) and high-risk loans (1) without any false positives.
Recall: 100% — The model successfully identified all actual positives for both categories without any false negatives..

## Summary

Based on the results, Logistic Regression is recommended as it performs exceptionally well for classification problems like this, where both predicting 0s (healthy loans) and 1s (high-risk loans) are equally important for maintaining financial stability and minimizing risk.

