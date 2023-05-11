# credit-risk-classification

## Overview of the Analysis

* The purpose of this analysis is to create a model that can accurately predict high-risk loans from information provided in the dataset.
* The dataset contained information on loan size, interest rate, borrower income, debt to income, total debt, and loan status
* The model tries to predict the loan status based on the dataset information provided in order to infer if future loans can be classified similarily to assess risk.
* The model splits the dataset into 72% of entries for training and 28% of entries for predicting/testing.
* The model uses logistic regression and random oversampling techniques to classify the data entries as healthy or high-risk

## Results

Results for each model's performance to capture the high-risk are listed below.

* Logistic Regression Model:
  * balanced accuracy = 95.0%
  * precision = 85%
  * recall = 91%
  * f1-score = 88%


* Logistic Regression Model with Random Oversampling:
  * balanced accuracy = 99.4%
  * precision = 85%
  * recall = 99%
  * f1-score = 91%

## Summary

* Logistic Regression Model with Random Oversampling performed better than the Logistic Regression Model without random oversampling. Although precision was the same for both models, the recall was considerably better in the oversampled model and thus allowed the model to classify the high risk data points more completely.