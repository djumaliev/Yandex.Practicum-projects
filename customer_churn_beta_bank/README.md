# YP_customer_churn

Yandex Practicum Data Science and Machine Learning Bootcamp: "Beta bank" customer churn.

Customers have started leaving "Beta Bank." Every month. Not many, but noticeably. Bank marketers calculated: retaining current customers is cheaper than attracting new ones.

It is necessary to forecast whether a customer will leave the bank in the near future or not. We are provided with historical data on customer behavior and contract terminations with the bank.

Build a model with the highest possible F1 score. To successfully complete the project, we need to achieve a metric of 0.59. Check the F1 score on the test set yourself.

Additionally, measure the AUC-ROC, compare its value with the F1 score.

Data source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

Research plan:

Open the data file, the file path: '/datasets/Churn.csv'.
Split the raw data into training and validation sets.
Examine the class balance, train the model without considering class imbalance. Briefly summarize the research findings.
Improve the model's quality, taking into account the class imbalance. Train different models and find the best one.
Conduct final testing.
Data should meet the following parameters.

Used lybraries:

pandas, matplotlib, numpy, sklearn
