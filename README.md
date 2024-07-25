# Credit-risk-classification
Challenge 20

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of this analysis is to predict if a loan is being healthy (0) or high-risk (1) using financial data.

I used logistic regression to classify our model into two categories. The analysis focused on financial data, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal was to predict the loan status, labeling it as either a healthy loan (0) or a high-risk loan (1).

The machine learning process included these steps:

Splitting data into labels (loan status).
Dividing the data into training and testing sets.
Choosing Logistic Regression as it classifies loans as healthy or high-risk.
Fitting the model with the training data.
Making predictions with the test data.
Evaluating the model’s performance using accuracy, precision, and recall scores.

## Results

Machine Learning Model: Logistic Regression

Accuracy: 99%
Precision and Recall Scores:
Healthy Loans (0):
Precision: 1.00
Recall: 0.99
F1-score: 1.00
High-Risk Loans (1):
Precision: 0.86
Recall: 0.92
F1-score: 0.89
Overall Averages:
Macro Avg:
Precision: 0.93
Recall: 0.96
F1-score: 0.94
Weighted Avg:
Precision: 0.99
Recall: 0.99
F1-score: 0.99

## Summary

The logistic regression model is the best performer. It predicts healthy loans (class 0) with perfect precision (1.00) and very high recall (0.99). For high-risk loans (class 1), it has good precision (0.86) and high recall (0.92). The overall accuracy is 99%, showing the model is very effective.

Does performance depend on the problem we are trying to solve?

Yes, performance depends on the problem. For loan classification, it’s more important to accurately predict high-risk loans (class 1) to avoid financial losses from defaults. While the model is excellent at predicting healthy loans, it could be better at predicting high-risk loans. The dataset is imbalanced, with many more healthy loans (18,723) than high-risk loans (661), which affects the model's performance for high-risk loans.

I recommend using the logistic regression model because it performs very well overall. To improve predictions for high-risk loans, gather more data on these types of loans. This would help balance the dataset and potentially make the model better at identifying high-risk loans, reducing financial risks.
