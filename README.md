# UTA-DataScience_Kaggle_Project

![UTA-DataScience-Logo](https://user-images.githubusercontent.com/98187543/207532661-e3253b61-25d9-4a0c-922c-aa2910b53f58.png)

## House Prices - Advanced Regression Techniques

* This github repo contains an attempt at the Housing Prices Kaggle Challenge. The goal of the challenge is to predict housing prices given 79 explanatory variables. This repository contains three different models for predicting the housing prices. https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

## Summary
### Data
* Some of the data used is the training set, testing set and description of the data which is also included in this repo.

### Processing/Clean-Up
* The first step was reading the data into a Jupyter Notebook.
* Next, split the Numerical and Categorical Variables and then used Python's get_dummies() command on the categorical variables to create dummy variables.
* Lastly, replace null values with the mean value for that column.

### Data Visualization
* Visualized the data by putting the numerical and categorical data on a histogram as well as plotting numerical data against the sale_price for the training data.

### Problem Formulation
* Three different models were utilized
* First, used "GradientBoostingClassifier" and "RandomForestClassifier" because they were both mentioned on the Kaggle website.
* Lastly, used "LinearDiscriminantAnalysis" as it was used in class

### Training
* The three models were trained using the curated data after the clean-up step.
* The GradientBoostingClassifier took by far the longest to train, it nearly took 15 minutes for the model to finish training.
* The other two classifiers were quicker to train and only took a couple of seconds.

### Results
* The Results of each model were then saved into a .csv file which can be accessed through this github repo
