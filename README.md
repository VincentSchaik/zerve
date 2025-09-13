# Auto MPG – Linear Regression Analysis

This repository contains a Python project developed in **Zerve** to explore and model the  
[Auto MPG dataset](https://archive.ics.uci.edu/ml/datasets/auto+mpg).  
The goal is to predict a car’s fuel efficiency (**miles per gallon**) using its numeric features.

## Overview
* Load and clean the Auto MPG dataset.
* Explore relationships between fuel efficiency and car characteristics.
* Build a **multiple linear regression model** using scikit-learn.
* Evaluate the model with a simple train/test split and with 5-fold cross-validation.

## Key Features
* **Data Preparation** – handle missing values and select numeric predictors.  
* **Visualization** – scatterplots and regression lines to reveal trends.  
* **Model Training** – multiple linear regression with predictors such as  
  cylinders, displacement, horsepower, weight, acceleration, and model year.  
* **Evaluation Metrics** – Root Mean Squared Prediction Error (RMSPE)  
  and R² (variance explained).  
* **Cross-Validation** – 5-fold cross-validation to estimate out-of-sample performance.
