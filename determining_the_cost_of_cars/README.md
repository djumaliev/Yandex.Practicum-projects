# YP_determining_the_cost_of_cars
Yandex Practicum Data Science and Machine Learning Bootcamp: Determining the cost of cars.

A used car sales service, "Not damaged, not painted," is developing an application to attract new customers. In it, you can quickly find out the market value of your car. You have historical data at your disposal: technical specifications, configurations, and prices of cars. You need to build a model to determine the cost.

The customer values:

- prediction quality;
- prediction speed;
- training time.

Research Procedure:

- Load the data from the file path: /datasets/autos.csv.
- Examine the data. Fill in missing values and handle anomalies in columns if any. Remove uninformative features among the characteristics.
- Prepare datasets for model training.
- Train different models, including at least one LightGBM and one non-boosting model. Try different hyperparameters for each model.
- Analyze training time, prediction time, and model quality for each model.
- Based on customer criteria, select the best model, and verify its quality on the test dataset.

Used lybraries:
pandas, numpy, seaborn, os, category_encoders, lightgbm, catboost(1.0.3), time, matplotlib
