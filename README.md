# credit-risk-classification

## Overview of the Analysis
The purpose of this analysis was to evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company was used to build a model that can identify the creditworhiness of borrowers. The data was split into testing and training sets and a logistic regression was performed with the original data. The model was then evaluated by calculating the accuracy score, generating the confusion matrix and by printing the classification report. The resampled training data was used to predict a logistic regression mdoel. The model's performance was evaluated by generating a confusion matrix and generating a classification report. 

## Results 
* Machine Learning Model 1:
  * Accuracy: 94.4%
  * Precision Healthy Loan : 1.00
  * Recall Score Healthy Loan: 1.00
  * Precision High-Risk Loan: 0.87
  * Recall Score High-Risk Loan: 0.89
 
* Machine Learning Model 2:
  * Accuracy: 99.6%
  * Precision Healthy Loan: 1.00
  * Recall Score Healthy Loan: 1.00
  * Precision High-Risk Loan: 0.87
  * Recall Score High-Risk Loan: 1.00

## Summary 
The logistic regression model has an accuracy score of 94%. It is important to note that the there are significantly more values for healthy loans than there are for high-risk loans. The precision and the recall for the healthy loans is found to be 0 while the precision and recall for the high-risk loan is at 0.87 and 0.89. The oversampled data fits well with the logistic regression model. The precision and recall for the healthy loan is still at 1.00. The precision and recall for the high-risk loan is at 0.87 and 1.00.
