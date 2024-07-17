# credit-risk-classification



## Overview

This repo utilizes a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. Using a logistic regression model, the code classifies loans as 'healthy' or 'high risk' informing potential lenders on the safety of each loan application.

## Process

The data is sourced from historical lending activity from a peer-to-peer lending services company. It includes information about each loan applicant including loan size, interest rate, income, debt to income rate, number of open bank accounts, derogatory marks, and total debt amount. Based on these metrics, the model will predict whether a loan should be classified as healthy or high risk. 

After reading the data into the notebook, the set is split into labels and features, in order to isolate the 'loan status' from the rest of the data. The set is then split into training and testing sets, and then fit using a logistic regression model. After the model makes its predictions, the performance is evaluated by generating a confusion matrix and classification report. 

## Results

<img width="476" alt="Screenshot 2024-07-17 at 2 13 55 PM" src="https://github.com/user-attachments/assets/9fe92d0b-b349-4f80-9dd7-76b4ad47de1d">


Accuracy Score: 0.99

The overall accuracy is very high, meaning it correctly classifies almost all of the loans.


Precision Score:

* Healthy (0): 1.00

* High Risk (1): 0.85

The precision score of healthy loans is perfect. For the high risk class, there is a 15% false positive rate, meaning some "Healthy" loans are misclassified as "High Risk."


Recall Score:

* Healthy (0): 0.99

* High Risk (1): 0.91

The high recall score of both "Healthy" and "High Risk" classes indicate a low false negative rate. The model successfully identifies most of the high-risk loans.


## Recommendation:

The overall success of the model for classifying both "Healthy" and "High Risk" loans makes it a highly useful tool for classifying loans. THe model is recommended for use due to its high accuracy, precision, and recall scores for both classifications of loans.
