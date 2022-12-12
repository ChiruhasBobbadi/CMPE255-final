# Black Friday sales prediction comparison using various regression models 

## Introduction

BlackFriday is one of the major days for retailers across United states the main aim of our project is to compare various regression models for our selected dataaset and this can help in choosing a suitable model next time when a prediction is to be done.

## Dataset

The dataset used in this study is a sales transaction data. It is publicly available on the following URL  [https://datahack.analyticsvidhya.com/contest/black-friday/](https://datahack.analyticsvidhya.com/contest/black-friday/). The Dataset comprises of about 550000 rows with 12 columsn about the Black Friday in a retail store. Our main aim is to compare the predictions of various regression models for predicting the black friday sales.

## Data Preparation
1. Used LabelEncoder for encoding the categorical columns like Age, Gender and City_Category
2. Used get_dummies form Pandas package for converting categorical variable State_In_Current_Years into dummy/indicator variables.
3. Filled the missing values in the Product_Category_2 and Product_Category_3

## Modelling
1. Random splitting of data into trainning and testing data in the ration of 80:20
2. Implemented regression models like Linear regression, Ridge regression, Lasso regression, Decision Tree regression, Random Forest regression, XGBoost regression.


## Evaluation Metric Used

We have used the value of RMSE as the evaluation metrics for various regression models, Root Mean Square Error (RMSE) is a standard way to measure the error of a model in predicting quantitative data. The model with the least RMSE is the ideal model. 

## Results & Conclusions

In this project various regression models like Linear regression, Ridge regression, Lasso regression, Decision Tree regression, Random Forest regression, XGBoost regression's are implemented and predictons are made subsequently their RMSE values are compared. Out of all these supervised models, based on the RMSE scores XGBRegressor was the best performer with a score of 2897.9


