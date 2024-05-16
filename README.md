# credit-risk-classification

## Overview of the Analysis

In this challenge, the logistric regression model was used to predict loan risk with healthy loan (0) or high-risk loan (1) labels. A dataset of historical lending activity from a peer-to-peer lending services company was used to build this model that identifies the creditworthiness of borrowers.

The steps used to complete this review are as follows: 
*  Read in the dataset
*  Separate the labels and features (in this case, loan_status was used as the label)
*  Split the data into test and training datasets using the train_test_split module from sklearn
*  Fit a logistic regression model with the training data using the LogisticRegression module 
*  Save the predictions on the testing data
*  Generate a confusion matrix
*  Print the classification report

## Results

Using logistric regression, here are the results from this model.

* Overall, this model has 99% accuracy, further broken down as follows:
    * Precision: The healthy loans labels were predicted at a 100% accuracy rate while high-risk loans were predicted at a 85% accuracy rate.
    * Recall: The healthy loans labels were predicted with a 99% accuracy rate and the high-risk loans were predicted at a 91% accuracy rate. 

## Summary

Given the 99% accuracy rate, I would recommend that the logistic regression model is used. When reviewing the healthy loan label predictors, both precision and recall are extremely high at 100% and 99% respectively. It would not be a fair recommendation without calling attention to the slight decrease in accuracy when it comes to the high-risk loan labels. The accuracy is slightly lower, coming in at 85% and 91%. In business, being able to correctly predict the high-risk loans is paramount. However, even though these are less accurate than the healthy loan label predictors, I find that these numbers are still acceptable and would move forward with recommending the model. 
