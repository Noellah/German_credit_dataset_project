# German credit dataset project

# Predicting credit risk & deploying model using Streamlit #

## By: Noel K. ##

### Project details ###

The aim of the project was to predict whether a person is of good or bad credit risk based on their attributes (features). Different machine learning models were explored to compare their performance. 
The models include CatBoost Classifier, eXtreme Gradient Boosting (XGBoost), Logistic Regression, Random Forest Classifier, Support Vector Machine(SVM), Linear Discriminant Analysis,  and Gradient Boosting Classifier.

Different pre-processing techniques including Ordinal encoding, One hot encoding (OHE), Normalization and SMOTEENN data balancing were implemented.

The F-beta score was used to evaluate the performance of the models. This is an unbalanced dataset so the F-beta measure is recommended and penalizes more a misclassification error where a bad customer is marked to have good credit score (optimizes recall, minimizes false -ve).

This is especially because if a bank lends money to a customer with a poor track record, but is classified as a good customer, it will ultimately cost the bank more than if they were to decline a loan to a customer with good track record, but is classified as a bad customer.

Gradient Boosting Classifier achieved the highest F-beta score of 0.7692.

Also a machine learning model(CatBoost) was deployed using Streamlit. This is a demonstration of a simple application that a non-technical person or data science expert can use to input customer's attributes and tell whether the person is likely to pay back a loan or not (good credit risk vs bad credit risk). More details on this can be found in the "german_credit_streamlit_app/" subfolder.

### Dataset ###
The UCI German credit dataset was used in this project - https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/german.data


