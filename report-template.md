# Module 12 Report Template

## Overview of the Analysis

This analysis predicts whether a loan is healthy (0) or high-risk (1) using machine learning. The dataset includes financial variables like loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. A Logistic Regression model is used for classification, following a process of data preparation, splitting, training, prediction, and evaluation.

## Results

Model: Logistic Regression

Healthy loans (0): Precision 1.00, Recall 0.99, F1-score 1.00
High-risk loans (1): Precision 0.86, Recall 0.94, F1-score 0.90

## Summary

The Logistic Regression model performs well, with high accuracy and strong recall for high-risk loans. While it slightly overpredicts high-risk loans, it correctly identifies most defaults. Since preventing defaults is a high priority, recall is possibly even more important than precision. The model’s 94% recall for high-risk loans ensures it flags most risky loans which is great.
