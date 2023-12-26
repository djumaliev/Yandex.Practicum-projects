# YP_research_on_the_scooter_rental_service
Yandex Practicum Data Science and Machine Learning Bootcamp: Research on the scooter rental service.

We have data on the GoFast scooter rental service. The data should include information about users from several cities and the trips they have made. To make trips around the city, GoFast service users use a mobile application. The service can be used:

Without a subscription:

No subscription fee;
Cost per minute of the trip — 8 rubles;
Start cost (beginning of the trip) — 50 rubles;
With an Ultra subscription:

Subscription fee — 199 rubles per month;
Cost per minute of the trip — 6 rubles;
Start cost — free.
There are several types of data for each user:

Unique ID
Name
Age
City
Subscription type
Information about their trips includes:

Unique ID
Distance
Duration
Travel date
About subscription types:
Subscription type:

Cost per minute of the trip
Start cost of the trip
Monthly payment cost
Main research hypotheses:

Do subscription users spend more time on trips?
Do subscription users not exceed the optimal distance of one trip at 3130 meters?
Check whether the revenue from subscription users is higher compared to users without a subscription.
Check, using the hypothesis of equality of means for dependent (paired) samples, whether the number of support requests decreased after the server update.
Also, it is necessary to check:

Find out the minimum number of clients to send promo codes to during the promotion so that the probability of not meeting the plan is approximately 5%.
Estimate the probability that no more than 399.5 thousand users will open a push notification out of 1 million notifications in total.
Research process:

Using data from the files '/datasets/users_go.csv', '/datasets/rides_go.csv', and '/datasets/subscriptions_go.csv', the first step is to determine the quality of the data.
Data preprocessing, error correction, filling in missing values, or removing anomalous values.
Data merging for research purposes.
Data analysis and calculation of key parameters.
Conclusions based on the analysis.

Used lybraries:

pandas, scipy, numpy, matplotlib.pyplot
