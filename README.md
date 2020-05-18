# Default_Credit
Meagan Rossi & Raam Levy

## Overview<br/>
The goal of this project is to find the model which best predicts whether a person will default on their loan by applying classification modeling. In doing so, we want to utilize all of the different tools we have learned over the course: data cleaning, EDA, feature engineering/transformation, feature selection, hyperparameter tuning, and model evaluation. The dataset comes customers default payments in Taiwan.

Process/Expectations<br/>
Clean up your data set so that you can do EDA. This includes handling null values, categorical variables, removing unimportant columns, and removing outliers.
Perform EDA to identify opportunities to create new features.
Great Example of EDA for classification
Using Pairplots with Classification
Create polynomial and/or interaction features. You must also create at least 2 new features that are not interactions or polynomial transformations. For example, you can create a new dummy variable that based on the value of a continuous variable (billamount6 >2000) or take the average of some past amounts.
Perform some feature selction. This can happen beforehand using F-scores, or you can do it as part of your model building process by looking at the weights of your regularized logistic regression or feature importance of your decision tree.
You must fit each of the three models to your data and tune at least 1 hyperparameter per model.
After identifying the best hyperparameters for each model, fit those models to the test set and identify the best model overall using the evaluation metric of your choice.
Present your best model.

## Tools
- KNN
- Random Forest
- XGBoost

**Data Sources**<br/>
UCI Machine Learning Repository [default of credit card clients Data Set](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#)
