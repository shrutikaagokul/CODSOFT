# Customer Churn Prediction using Machine Learning

## Objective
To build a machine learning model that predicts whether a customer will churn based on demographic, financial, and behavioral data.

## Dataset
Bank customer churn dataset containing customer details such as credit score, age, balance, activity status, and churn information.

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Logistic Regression

## Methodology
1. Removed non-informative columns such as customer ID and names
2. Encoded categorical features using one-hot encoding
3. Split the dataset into training and testing sets
4. Trained a Logistic Regression model
5. Evaluated the model using accuracy and classification report

## Results
The Logistic Regression model achieved an accuracy of approximately **80%** on the test dataset.

## Discussion
While the overall accuracy is strong, the classification report indicates lower recall for churned customers due to class imbalance. This highlights a common challenge in real-world churn prediction problems.

## Conclusion
This project demonstrates how machine learning can be applied to predict customer churn and emphasizes the importance of understanding evaluation metrics beyond accuracy.
