# credit-risk-classification

This analysis will use various techniques to train and evaluate a model based on loan risk. We will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The target information we are trying to predict is the classification of the loan status. We will use the below financial information as features in the dataset: 
    -Loan size 
    -Interest rate 
    -Borrower income 
    -Debt to income ratio
    -Number of accounts 
    -Derogatory marks
    -Total debt

The two variables we are trying to predict are value '0'(healthy loans) and value '1'(high risk loan). 

Stages of machine learning
    Step 1: Read the `lending_data.csv` data from the `Resources` folder into a Pandas DataFrame.
    Step 2: Create the labels set (`y`)  from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
    Step 3: Split the data into training and testing datasets by using `train_test_split`.
    Step 4: Fit a logistic regression model by using the training data (`X_train` and `y_train`).
    Step 5: Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
    Step 6: Evaluate the model’s performance by using a confusion matrix and classification report 

The logistic regression model predicts a health loan with 100% accuracy and a high risk loan with 85% accuracy. The balanced accuracy is 92%. 