# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
**balanced_accuracy_score = 0.9520479254722232
**precision 0=1.00, 1=0.85
**recall 0=0.99, 1=0.91

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
**balanced_accuracy_score = 0.9947308560359689
**8precision 0=0.99, 1=0.99
**recall 0=0.99, 1=0.99
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

ortant to predict the `1`'s, or predict the `0`'s? )

**The RandomOverSampler seems to perform best because it detects more of the potential people who are likely to default on loans based on their credit risk.

**Thee performance depends on the problem you are trying to solve. we are not concerned about overclassifying the good loans.  we are more concerned about increasing the 1's classification.

If you do not recommend any of the models, please justify your reasoning.
**I only recomamnd the RandomOverSampler model to be used for this problem becouse it
detects more of the potential people who are likely to default on loans based on their credit risk.
