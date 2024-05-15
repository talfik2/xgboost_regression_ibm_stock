# XGBoost application for IBM Stock Price Data

In this repo, I applied `XGBoostRegressor` to IBM Stock Price Data(1962-Present) from yfinance library of Python. The task is to predict the Closing values of the stock prices. In this study, I've compared the effect of Hyperparam Tuning on model performances.
For this purpose, 
- First, I've used XGBoost by setting learners as `Decision Tree Regressor` and `Linear Regression` without tuning hyperparameters.
- Then, I've tuned the hyperparameters. I've used `GridSearchCV` for Hyperparameter Tuning.
- Lastly, I've compared the model performance with and without hyperparameter tuning.
As XGBoostRegressor is a regression algorithm, I  **RMSE(Root Mean Square Error)** for evaluation metric.
 
