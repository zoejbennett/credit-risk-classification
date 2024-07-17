# credit-risk-classification



## Overview

This repo utilizes a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. Using a logistic regression model, the code classifies loans as 'healthy' or 'high risk' informing potential lenders on the safety of each loan application.

## Process

After reading the data into the notebook, the set is split into labels and features, in order to isolate the 'loan status' from the rest of the data. The set is then split into training and testing sets, and then fit using a logistic regression model. After the model makes its predictions, the performance is evaluated by generating a confusion matrix and classification report. 

## Results

<img width="476" alt="Screenshot 2024-07-17 at 2 13 55 PM" src="https://github.com/user-attachments/assets/9fe92d0b-b349-4f80-9dd7-76b4ad47de1d">

### Summary:

The model predicts "Healthy" loans with near-perfect accuracy, precision, and recall.
For "High Risk" loans, the model performs well but not as perfectly, with a precision of 0.85 and a recall of 0.91.
The slightly lower performance suggests that the model can misclassify "Healthy" and "High Risk" loans. As only 1 in 30 loans are classified as high risk, there is a likelyhood for the model to have a bias towards classifying a loan as healthy.
The high accuracy and weighted averages indicate that the model handles the predominant class of "Healthy" loans very well, and still performs strongly on the less common "High Risk" loans.
