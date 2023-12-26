# YP_taxi_order_forecasting
Yandex Practicum Data Science and Machine Learning Bootcamp: Taxi order forecasting.

The company "Cheerful Taxi" has collected historical data on taxi orders at airports. To attract more drivers during peak periods, it is necessary to forecast the number of taxi orders for the next hour. Build a model for such prediction.

The RMSE metric value on the test set should not exceed 48.

Research Steps:
Load the data and resample it on an hourly basis.
Analyze the data.
Train different models with various hyperparameters.
Create a test set comprising 10% of the original data. Choose a model based on the RMSE metric with a requirement of <= 48.
Validate the model using the test set.
The data is available in the file taxi.csv, and the number of orders is located in the column named num_orders.

Used lybraries: pandas, numpy, seaborn, os, category_encoders, lightgbm, catboost(1.0.3), time, matplotlib
