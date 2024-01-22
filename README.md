## Overview of the Analysis

In this analysis, the purpose was to build and evaluate machine learning models for credit risk analysis. The dataset contained financial information on loans, and the goal was to predict whether a loan is healthy (label 0) or high-risk (label 1). The main stages of the machine learning process included data loading, preprocessing, splitting into training and testing sets, model building (using Logistic Regression), and evaluation.

To address the imbalanced nature of the dataset, two approaches were used:

Original Model: Logistic Regression trained on the original data.
Resampled Model: Logistic Regression trained on the data oversampled using RandomOverSampler.

## Results

* Machine Learning Model 1:
  Balanced Accuracy Score: 95.21%
  Precision (label 1): 86%
  Recall (label 1): 91%

* Machine Learning Model 2:
  Balanced Accuracy Score: 99.41%
  Precision (label 1): 85%
  Recall (label 1): 99%

## Summary

The Resampled Logistic Regression model is recommended for credit risk analysis due to its exceptional performance in accurately predicting high-risk loans. The higher recall for label 1 indicates its effectiveness in capturing a significant portion of actual high-risk cases.

The final decision may also consider business priorities and the trade-off between precision and recall. If correctly identifying high-risk loans is a top priority, the Resampled Model is well-suited for deployment.

In conclusion, the Resampled Logistic Regression model stands out as the preferred choice for credit risk analysis, providing a robust solution for identifying potential credit risks with high accuracy.
