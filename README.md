# credit-risk-classification
Modulle 20 Challenge. 

## Overview of the Analysis
    
    Module 20 was about credit card risk classification. So, using a machine learning model will help determine which loans are un-healthy (high-risk) or healthy (low-risk). Using the Logistic Regression model we will be able to predict whether the loan will be high or low risk based on the loans staus of the company.

## Results

    Logistic Regression Model with Original Data: 
    * The balanced accuracy score has around 96%
    * In the recall score, there was 1% mistakes for low-risk and 6% mistakes for high-risk
    * Due to the imbalanced data, there is a higher possibility that that high-risk will be mistaken for low-risk and vice versa. 

    Logistic Regression Model with Oversampled Data:
    * The balanced accuracy score was around 99% 
    * In the recall score, both low-risk and high-risk had a mistake of 1% which is definite improvement. 
    * There is a lower possibility that there would be a mistake between low-risk and high-risk. 

## Summary

    Comparing the two logistic regression model, the model with the oversampled data had a better recall compared to the original data. If I had to recommend a specific model, it would be the logistic regression model fitted with the oversampled data. 