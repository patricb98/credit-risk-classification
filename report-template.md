# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

This analysis will use various techniques to train and evaluate a model based on loan risk. We will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* Explain what financial information the data was on, and what you needed to predict.

The target information we are trying to predict is the classification of the loan status. We will use the below financial information as features in the dataset: 
    -Loan size 
    -Interest rate 
    -Borrower income 
    -Debt to income ratio
    -Number of accounts 
    -Derogatory marks
    -Total debt


* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The two variables we are trying to predict are value '0'(healthy loans) and value '1'(high risk loan). 

* Describe the stages of the machine learning process you went through as part of this analysis.

Stages of machine learning
    Step 1: Read the `lending_data.csv` data from the `Resources` folder into a Pandas DataFrame.
    Step 2: Create the labels set (`y`)  from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
    Step 3: Split the data into training and testing datasets by using `train_test_split`.
    Step 4: Fit a logistic regression model by using the training data (`X_train` and `y_train`).
    Step 5: Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
    Step 6: Evaluate the model’s performance by using a confusion matrix and classification report 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithm).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
