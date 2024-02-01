Bulldozer auction prize prediction using RandomForest Regressor

In this project, I have applied machine learning models to predict the future sale prices of heavy equipment at auction based on it's usage, equipment type, and configuration. Here In the project for the evaluation of the model Root Mean Square Log Error(RMSLE) is used.

The project steps involve:
1. Importing necessary libraries, models, and functions.
2. Getting the dataset from the source (https://www.kaggle.com/c/bluebook-for-bulldozers/data)
3. Data preparation (handling null values, removing unnecessary data, etc)
4. Visualisation to analyze the data correlation and output dependency on the data features.
5. Selecting the classifier (https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)
6. Making train and test sets and training the classifiers to obtain baseline models and eliminating some models based on accuracy.
7. Model evaluation using RMSLE, R2 score, MSE, etc.
8. Hyperparameter tuning using RandomSearchCV and GridSearchCV.
9. Finding the effective features using the model.

This tutorial attempts to explain the workflow in Machine Learning for solving Regression problems. One key highlight of this project is the clear 
demonstration of the different ways for handling the missing values in a dataset alongside feature engineering.
