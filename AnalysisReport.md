## Overview of the Analysis
The purpose of this analysis is to evaluate the performance of the logistic regression model. Using the a CSV on loan data to help process our data for our model. The CSV provided interest rate, borrower income, debt to income, number of accounts, total debt, and loan status.
Using the loan status as the y variable and all the other columns as our X variable, I split the data into training and testing datasets using the train_test_split from sklearn. Then I created the logistic regression model by using the training data to fit my model. Selecting my classifer to random_state 1 and fitting it to the X_train and the y_train variables previously set. The confusion matrix helped provide a score to see the accuracy of the model. It helped us predict weather there is a healthy loan or if a loan is high risk. The logistic regression definitely made an accurate prediction for the healthy loans. It missed one percent of the healthly loans. The f1-score reflects that there is a perfect balance between precision and recall. For the high-risk loan, the model predicts 85% of the loans correctly. The recall identifies that 91% was identified by the model. Overall the f1-score is 0.88, meaning that their is a good balance, but can still make improvements to help that score go up.



## Results
Accuracy score for healthy loans are 99%
Scores For Healthy Loan
1. Precision Score: 1.00
2. Recall Score: 0.99
3. f1-score: 1.00

Accuracy score for high risk loans are 85%
Score For High Risk Loan
1. Precision Score: 0.85
2. Recall Score: 0.91
3. f1-score: 0.88


* Machine Learning Model 1:
    Overall the Accuracy, Precision, and Recall scores were almost always correct for detecting healthy loans and 85% correct for high risk loans. There is room for improvement, but in general a high rate of accuracy.

## Summary

Logistic regression is a great model to use when for loan criteria. In specific to see if one qualifies for a healthy loan versus high risk loan.

_______________________________________________________________________________________________
