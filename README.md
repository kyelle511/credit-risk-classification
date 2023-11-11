# credit-risk-classification
Module 20 - Supervised Learning <br>
Contributor: Katy Yelle

## Repository Structure
    -Main Folder
        -.gitignore
        -README.md

    -Sub Folders
        -Credit_Risk
          -Resources
            -lending_data.csv
          -credit_risk_classification.ipynb

## Overview of the Analysis

This analysis uses a dataset of historical lending activity from a peer-to-peer lending services company to build a Logistic Regression model that can identify the creditworthiness of borrowers.  

The data features include: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt. The y target values includes 75036 with a healthy loan status ("0"), and 2500 with a high-risk status ("1").


## Results

* Machine Learning Logistic Regression Model:
  * Overall Accuracy (99%)
  * Healthy Loan Precision (100%), Recall (100%)
  * High-Risk Loan Precision (87%), Recall (89%)

## Summary

The model is impacted by the imbalanced classes, the greater number of healthy loans outweighs the number of high-risk loans, impacting the accuracy of the model. However, with a precision of 87% and recall of 89% for the high-risk category it is an okay model.  If the company is interested in improving the model's ability to predict high-risk loans a new model should be created that adjusts for the oversampling. 


