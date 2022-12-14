# UTA-DataScience_Kaggle_Project

![UTA-DataScience-Logo](https://user-images.githubusercontent.com/98187543/207532661-e3253b61-25d9-4a0c-922c-aa2910b53f58.png)

## House Prices - Advanced Regression Techniques

* This github repo contains an attempt at the Housing Prices Kaggle Challenge. The goal of the challenge is to predict housing prices given 79 explanatory variables. This repository contains three different models for predicting the housing prices. https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

## Summary

Three different regression models were used to estimate the pricing of the homes; Gradient Boosting, Random Forest and Linear Discriminant Analysis. These three methods were then compared to one another based on accuracy of the models. It was then found that the Random Forest Classifier resulted in the least amount of error.

### Data
* The data used is the training set, testing set and description of the data which is also included in this repo.
* Size: 957.39 kB
* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here

### Processing/Clean-Up
* The first step was reading the data into a Jupyter Notebook.
* Next, split the Numerical and Categorical Variables and then used Python's get_dummies() command on the categorical variables to create dummy variables.
* Lastly, replaced null values with the mean value for that column.

### Data Visualization
* Visualized the data by putting the numerical and categorical data on a histogram as well as plotting numerical data against the sale_price for the training data.

The following is the distribution of all of the quantitative data for the training set:
![Quantitative](https://user-images.githubusercontent.com/98187543/207727309-bbf234bb-f345-4c07-a00d-3ae32c440f51.jpg)

Next, is plotting the quantitative data against the sale price in the training set:
![QuantVsSalePrice](https://user-images.githubusercontent.com/98187543/207727447-3b1e9ea4-156a-4bf9-b0eb-2b42aaa4a487.jpg)

Now, let's take a look at specifically the year the home was built against the sale price:
![YrBuiltVsSalePrice](https://user-images.githubusercontent.com/98187543/207727610-02c578a6-9419-4ecb-bda1-82a165984d9e.jpg)

Finally, visualizing the distribution of the categorical variables:
![Categorical](https://user-images.githubusercontent.com/98187543/207728252-7d2a4742-56b4-491c-b11e-b2a592556674.jpg)

### Problem Formulation
* After processing and cleaning the data three different methods were utilized and trained to predict housing prices.
The models trained:
* Gradient Boosting
* Linear Discriminant Analysis
* Random Forest

### Training
* Python Packages: pandas, numpy, matplotlib.pyplot, HTML, display, sklearn

### Results
* The prediction on the test set of each model were each saved to a .csv file which can be accessed through this github repo
* Furthermore, a distribution of the predicted prices on the testing set was also found

Gradient Boosting:

![Gradient](https://user-images.githubusercontent.com/98187543/207729738-aaf1d9a5-9e54-4211-af82-340328b9041b.jpg)

Linear Discriminant Analysis:

![LDA](https://user-images.githubusercontent.com/98187543/207729830-8b6199e8-6b0d-475e-8989-967aab416768.jpg)

Random Forest Classifier:

![RandomForestClassifier](https://user-images.githubusercontent.com/98187543/207729933-c2a4968c-86db-40b9-a133-4bc981023431.jpg)

# Performance Comparison
Lastly, the comparison of the different methods and their accuracy:
![Results](https://user-images.githubusercontent.com/98187543/207730359-1c2d87f3-7987-46cf-a77d-909fee70ebca.png)


(All results can be found in this github repo.)
