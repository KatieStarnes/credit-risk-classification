# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to determine the creditworthiness of borrowers using a logistic regression model. The model was based on data made up of loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and the total debt of a borrower of a loan in the data set. Using this data will will predict whether or not the loan healthy (0), or if the loan has a high risk of defaulting (1).

The stages of the machine learning process included loading the CSV file into a Pandas Dataframe, splitting the dataset into training and testing sets, using a Logistic Regression model, and using a confusion matrix to analyze the accuracy of the model.


## Results

* Logistic Regression Model Results

    * Healthy Loans (0)
        * Percision = 1.00
        * Recall = 1.00
    
    * High Rish Loans (1)
        * Percision = 0.87
        * Recall - 0.89

    * Accuracy = 0.99


## Summary

The logistic regression model predicts the healthy loan '0' at perfect accuracy with a percision of 1.00 and high-risk loan '1' with lower accuracy at 0.87 and a recall of 0.89, however that is still considered an acceptable success rate (above 0.80).

I recomend a Logistic Regression Model for predicting creditworthiness of borrowers.
