# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
Analyze the risk of default on loans to current clients
* Explain what financial information the data was on, and what you needed to predict.
The financial information of their clients did not give them a clear perspective on risk loans 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The variable value_counts we want to know how the data of our exercise is distributed.
* Describe the stages of the machine learning process you went through as part of this analysis.
First we separate the data into labels we begin to use different sklearn models to obtain the data we are looking for until we predict the model and the oversampler is used to re-evaluate the exercise
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
I use the classification_report method because we are looking for a data based on a series of customer data to obtain a specific result for each one
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
 The balanced accuracy score is 95.2%. Comparing that to the balanced accuracy score of 99.3% for the oversampled data, we can observe that the balanced accuracy score for the oversampled data is higher.
The Original Model produced a precision of 0.85 and the Oversampled Model data produced a precision of 0.84, the original model did slightly better at making predictions for the high risk (1).
The Original Model produced a recall of 0.91. The Oversampled Model data produced a recall of 0.99, the Oversampled Model data was more accurate at credit risk.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? 
Model regression may be enough to obtain an acceptable result, but in my opinion I would always prefer to use oversampled just to check that the data were correct in the first model.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
In the exercise, I focused more on obtaining high-risk data, but I think that the important thing for this company is to obtain information from clients healthy risk to sell them financial services.
If you do not recommend any of the models, please justify your reasoning.
I recommend.
