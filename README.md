# House_price_Prediction
Housing prices are an important reflection of the economy, and housing price ranges are of great interest for both buyers and sellers. In this project, house prices per unit sqft will be predicted given explanatory variables that cover many aspects of houses. The goal of this project is to create a regression model that are able to accurately estimate the price of the house given the features.

## Problem statement:
The goal is to understand the relationship between house features and how these variables affect the house price. Using more than one model, predicting the price of the house using the given dataset. Comparing the accuracy of the models along with the drawbacks of each technique's.

### Objectives: 
Predict the Price per sqft for each House.
Minimize the difference between predicted and actual rating (RMSE/MSE)

* Mapping the real world problem to a Machine Learning Problem: 
This problem involves predicting the prices of the houses per unit sqft which are continuous and real valued outputs. Thus, this is a Regression Problem.

### Performance Metric:

Using Root Mean Square Error(RMSE) as the performance metric . To know more about it please click on : “Root Mean Square Error” .
Mean Absolute Error to know the absolute deference between Actual and Predicted values

## Machine Learning Objective and Constraints:

* Minimize RMSE. Try to provide some interpretability.
* This is a Regression problem, so applying the regression models such as
    * Linear Regression
    * Lasso
    * Ridge 
    * Gradient Decent Boosting Regressor 
    * ElasticNet 
    * Stochastic Gradient Boosting Regressor 
    * Random Forest Regressor 
    * XG Boost Regressor
    
By checking the MAE, RMSE, R2 score and Accuracy score, i observed that XG boost Regressor has performed well, with the accuracy of 85.05
