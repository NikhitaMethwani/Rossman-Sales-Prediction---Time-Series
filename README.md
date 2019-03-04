# Rossman-Sales-Prediction
The focus of this project was to predict the Sales Price of the Rossman Stores.
The dataset consists of Train , Test and Store datasets which contain the data for 1115 Rossman Stores.

The features in the dataset that are affecting the Sales of the Rossman Stores are taken into consideration during forecasting of the Sales.

Two Modelling techniques such as SARIMAX and XGBoost have been trained for predicting the Sales.

There were seasonal trends in the dataset and SARIMAX model still couldnt provide a Root mean Square Percentage error(RMSPE) of less than 1.0

XGBoost model with hyperparameter tunning and proper features with 6000 iterations and early stoopin of 100 acheived the RMSPE which is top 10 of the Kaggle competition.
