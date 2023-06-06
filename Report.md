# Module 12 Report

## Overview of the Analysis

* The purpose of this analysis is to build a model that evaluates the creditworthiness of borrower
* The information provided in the data is loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.
* We are trying to predict loan status and if the borrower is a good match for receiving credit.
* I split the data into training and test sets, created the labels set (`y`)  from the “loan_status” column, created the features (`X`) DataFrame from the remaining columns, checked the balance of the labels variable (`y`) by using the `value_counts` function, split the data into training and testing datasets by using `train_test_split`, fit a logistic regression model by using the training data (`X_train` and `y_train`), saved the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model, and evaluated the model's performance.
* I used logistic regression and resampled data.

## Results

* Machine Learning Model 1:
  *Accuracy: 95.2%
  *Precision: 99%
  *Recall: 99%


* Machine Learning Model 2:
  *Accuracy: 99.4%
  *Precision: 99%
  *Recall: 99%


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
*It seems that the second model performed better due to the accuracy score. I recommend using the second model because of this. It is more important to predict the indicator that proves a borrower to be less responsible and less worthy of credit.