# Customer-Churn-Prediction-using-Spark
## Overview
In this project, I use the customer behavioral data of a fictitious music app company, Sparkify, to create a model that predicts customers who are most likely to churn.I used three different models : Logistic Regression Model, Linear SVC Model and Random Forest Model. Based of F1 scores, Random Forest Classifiers performed the best. F1 score as evaluation metric was suitable for this scenario, because our dataset was imbalanced. The Random Forest model achieved a best F1 score of 0.858. Most useful feature turned out to be : Number of active days.

## Files in the repo
1. Readme
2. Sparkify.ipynb

## Packages used
PySpark, Pandas, Matplotlib, Seaborn, Plotly

For blogpost related to this project, please visit : https://medium.com/@anand9499/customer-churn-prediction-using-apache-spark-5ce8103934ac 
