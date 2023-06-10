# About The Project

This is an Application that trains a model using supervised learning and imbalanced-learn library in order to classify and identify the creditworthiness of borrowers.


### Built With

* Python
* Python CSV Reading/Writing
* Python pandas
* Python hvplot.pandas
* Python conda
* Python JupyterLab

## Overview of the Analysis

* The purpose of the analysis is to train a model that can classify and identify the creditworthiness of borrowers
* The dataset is of historical lending activity from a peer-to-peer lending services company, and what you are trying to predict are the people who are likely to default on a loan.
* The variables that is being predicted is the y_prediction. I start with the y_variable which holds the values of the loan_status column and use the value_counts method to see the count of good and bad loans in the dataset. I use this information to build the test data for training and prediction.

* I build two models and used LogisticRegression method on one, and RandomOverSampler on the other.

## Results

# Machine Learning Model 1 LogisticRegression:

* balanced_accuracy_score = 0.9520479254722232
* precision 0=1.00, 1=0.85
* recall 0=0.99, 1=0.91

# Machine Learning Model 2 RandomOverSampler:
* balanced_accuracy_score = 0.9947308560359689
* precision 0=0.99, 1=0.99
* recall 0=0.99, 1=0.99

## Summary

*The RandomOverSampler seems to perform best because it detects more of the potential people who are likely to default on loans based on their credit risk.

*The performance depends on the problem you are trying to solve. we are not concerned about overclassifying the good loans . we are more concerned about increasing the 1's classification.

*I only recommend the RandomOverSampler model is used for this problem.

---
## Contributors
By AlGhalia Alsammak
Email:galsammak@gmail.com
## License
CU
