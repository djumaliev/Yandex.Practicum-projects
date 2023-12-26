# YP_location_selection_for_a_well

Yandex Practicum Data Science and Machine Learning Bootcamp: Location Selection for a Well.

Project Description:
The task at hand is to decide where to drill a new well for the "MainRussianStateOil" extraction company.

We have samples of oil from three regions: 10,000 deposits in each, where the quality of oil and the volume of its reserves have been measured. Build a machine learning model that will help determine the region where extraction will bring the greatest profit. Analyze potential profits and risks using the Bootstrap technique.

Steps for selecting a location:

- In the chosen region, identify deposits and determine the values of features for each.
- Build a model and estimate the volume of reserves.
- Select deposits with the highest estimated values. The number of deposits depends on the company's budget and the cost of developing one well.
- Profit is equal to the total profit from the selected deposits.

Research steps:

1. Open data files with paths: '/datasets/geo_data_0.csv', '/datasets/geo_data_1.csv', '/datasets/geo_data_2.csv'.
2. Train and test the model for each region.
3. Perform profit calculations.
4. Write a function for calculating profits based on selected wells and model predictions.
5. Evaluate risks and profits for each region.

The data should have the following parameters:

id: a unique well identifier.
f0, f1, f2: three features of the points (it doesn't matter what they represent, but the features themselves are significant).
product: volume of reserves in the well (thousands of barrels).

Used lybraries: pandas, seaborn, matplotlib, scikit-learn
