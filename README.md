# Hyperparameter Tuning for Customer Churn Prediction

This project demonstrates how to improve machine learning model performance through Hyperparameter Tuning using Scikit-learn. The notebook uses the Customer Churn Prediction dataset and compares multiple machine learning models before optimizing their hyperparameters.


# Project Overview

Hyperparameter tuning is an essential step in the machine learning lifecycle. Instead of using default model parameters, this project searches for the best combination of hyperparameters to maximize predictive performance.

    The notebook includes:

        Data preprocessing
        Feature encoding
        Feature scaling
        Model training
        Hyperparameter tuning
        Model evaluation
        Performance comparison

# Dataset

The project uses the Customer Churn Modelling Dataset.

# Features
Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary

## Target Variable
Exited (Customer Churn)


# Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
Jupyter Notebook



# Data Preprocessing
The notebook performs several preprocessing steps:

Remove unnecessary columns
Handle categorical variables
Label Encoding
One-Hot Encoding
Feature Scaling using StandardScaler
Train-Test Split


# Machine Learning Models

The notebook trains and compares multiple classification models, including:

Logistic Regression
Random Forest Classifier
XGBoost Classifier


# Hyperparameter Tuning

The notebook focuses on improving model performance by tuning hyperparameters.

Typical parameters include:

# Random Forest

Number of Estimators
Maximum Depth
Minimum Samples Split
Minimum Samples Leaf

# 
XGBoost
Learning Rate
Maximum Depth
Number of Estimators


# Evaluation

Accuracy Score
Precision Score
Recall Score
F1 Score
ROC-AUC Score

These metrics help determine the best-performing model after tuning.