# ML_Data_Cleaning_and_Feature_Selection_Chronic_Kidney_Disease_Prediction
## Chronic Kidney Disease Prediction

This repository containts two files -
1. Assignment 1 - ML Data Cleaning & Feature Selection.ipynb
2. new_model.csv

## Background
Chronic Kidney Disease (CKD) is a condition where the kidneys gradually lose function over a period of time, usually months to years. This can lead to a buildup of waste products and fluids in the body, as well as an imbalance of important electrolytes. The disease can be caused by a number of factors, including diabetes(Sugar levels), high blood pressure, Hemoglobin and other diseases that affect the kidneys. The data is provided for almost 400 patients and we are required to build an intelligent model that can predict if the patient will be prone to disease based on several medical parameters .

## What is our ultimate aim with this notebook?
Our ultimate aim is to build a machine learning model that can predict if the person is suffering from Chronic Kidney Disease based on sevrral medical parameters as mentioned above. Before we create a model we need to do some data cleaning, feature selection and exploratory data analysis of the kaggle dataset.

#### Kaggle Dataset Link: https://www.kaggle.com/datasets/abhia1999/chronic-kidney-disease

## We will try to answer the following questions --
What are the data types? (Only numeric and categorical)

Are there missing values?

What are the likely distributions of the numeric variables?

Which independent variables are useful to predict a target (dependent variable)? (Use at least three methods)

Which independent variables have missing data? How much?

Do the training and test sets have the same data?

In the predictor variables independent of all the other predictor variables?

Which predictor variables are the most important?

Do the ranges of the predictor variables make sense?

What are the distributions of the predictor variables?

Remove outliers and keep outliers (does if have an effect of the final predictive model)?

Remove 1%, 5%, and 10% of your data randomly and impute the values back using at least 3 imputation methods. How well did the methods recover the missing values? That is remove some data, check the % error on residuals for numeric data and check for bias and variance of the error. For categorical data, calculate the accuracy and a confusion matrix.
