# Credit Risk Classification Report

## Overview of Analysis

For most financial institutions credit risk arises from the potential that a borrower will fail to fulfill the financial obligation of a loan and this remains to be one of the largest and most obvious soruces of credit risk for these institutions. The goal of the Credit Risk Classification machine learning model is to identify the creditworthiness of borrowers based on training data from a dataset of historical lending activity from a peer-to-peer lending services company.

The dataset included 19,384 lending records which included features of loan size, interest rate, borrower income, debt to income ratio, number of accounts, number of derogatory marks, total debt, and finally a loan status. The loan status variable included binary classification values of 0 and 1, with 0 representing a healthy loan and 1 representing a credit-risk loan. Thus, loan status would be used as the dependent y-variable for our machine learning model and all other features would be used as independent x-variables with which a resulting loan status would be determined.

For this analysis, a logisitic regression machine learning model was used to determine proper classification of loan status. The lending data was first imported, formatted into a dataframe, and analyzed to determine appropriate variable selection. Labels for the supervised learning model were created from the dataframe by seperating the loan status as the y-variable from the rest of the features, the x-variable. The data was then split into training and testing datasets that would be used to fit the logistic regression model. Once fit with x and y training data, the logistic regression model was then fed feature testing data to create predictions on loan statuses. The predictions were then evaluated against the original y testing data in a confusion matrix and a classification report detailing number of true positives and negatives and false positives and negatives, along with precision, recall, and accuracy scores.

## Results

## Summary
