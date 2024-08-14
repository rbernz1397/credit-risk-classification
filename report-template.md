# Overview of Analysis

In this analysis, we assesed how well different machine learning models could predict healthy vs. risky loans based on financial data. The data included details like loan interest rate and borrower income. We wanted to predict whether a loan may default, marking it as a '1' or a '0'.

We split the data into two sets - one for training the model and one for testing it. We used a logistic regression model which turned out to have a 99% accuracy score. This means the model did a great job at predicting the default and non-default loans.

# Results:

Logistic Regression:
    - Accuracy: 99%
    - Precision for non-defaults: 100%
    - Precision for defuaults: 85%
    - Recall for non-defaults: 99%
    - Recall for defaults: 91%

# Summary:

The logistic regression model worked very well with a 99% accuracy score. This shows  that it is good at predicting whether or not a loan will default. It also had high precision and recall scores, meaning it correctly identified defaults most of the time. If the priority is high classification accuracy, then the logistic regression model is recommended. However, it's important to consider whether the high accuracy may be due to class imbalance or overfitting. Other models may be necessary to ensure a comprehensive risk assessment.
