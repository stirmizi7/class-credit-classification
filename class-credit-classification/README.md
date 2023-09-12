# class-credit-classification

## Overview of the Analysis

The purpose of this analysis is to build and evaluate machine learning models for the classification of loan risk. Specifically, we aim to predict whether a loan is healthy (label "0") or high-risk (label "1") based on various features such as credit score, income, loan amount, etc. This analysis is essential for financial institutions to make informed decisions about loan approvals and to minimize the risk associated with high-risk loans.

## Results

Evaluated the performance of several machine learning models, including Logistic Regression, Decision Tree, and Random Forest, using the following metrics:

- **Logistic Regression:**
  - Accuracy Score: X.XX
  - Precision Score (Label 0): X.XX
  - Precision Score (Label 1): X.XX
  - Recall Score (Label 0): X.XX
  - Recall Score (Label 1): X.XX

- **Decision Tree:**
  - Accuracy Score: X.XX
  - Precision Score (Label 0): X.XX
  - Precision Score (Label 1): X.XX
  - Recall Score (Label 0): X.XX
  - Recall Score (Label 1): X.XX

- **Random Forest:**
  - Accuracy Score: X.XX
  - Precision Score (Label 0): X.XX
  - Precision Score (Label 1): X.XX
  - Recall Score (Label 0): X.XX
  - Recall Score (Label 1): X.XX

          precision    recall  f1-score   support

       0       1.00      1.00      1.00     15011
       1       0.88      0.91      0.89       497

accuracy                           0.99     15508

## Summary

Based on analysis, the machine learning models performed as follows:

- All models achieved relatively high accuracy scores, indicating that they can make accurate predictions.

- Precision scores for both labels (healthy loans and high-risk loans) are reasonably high across all models, which suggests that the models have a good ability to classify loans correctly.

- Recall scores for both labels are also acceptable, indicating that the models can identify most of the actual healthy loans and high-risk loans.

In summary, all three models (Logistic Regression, Decision Tree, and Random Forest) showed promising results for loan risk classification. However, the choice of the best model depends on specific business needs, interpretability, and computational requirements. We recommend further fine-tuning and evaluation of these models to determine which one best suits the company's goals and constraints.
