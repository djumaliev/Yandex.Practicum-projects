# YP_research_of_apartment_sale_listings
Yandex Practicum Data Science and Machine Learning Bootcamp: Research of apartment sale listings.

Study of Apartment Sale Listings
We have access to data from the Yandex.Real Estate service—an archive of apartment sale listings in St. Petersburg and neighboring areas spanning several years. Our goal is to establish parameters. This will enable the development of an automated system capable of detecting anomalies and fraudulent activities.

Two types of data are available for each apartment for sale. The first type is entered by the user, while the second type is automatically obtained based on cartographic data. For instance, this includes distances to the city center, airport, nearest park, and body of water.

1. Research Objectives
In this study, we aim to identify relationships between specific factors and determine the most influential aspects on real estate pricing, including:

- 'Price' and 'Total Area'
- 'Price' and 'Living Area'
- 'Price' and 'Kitchen Area'
- 'Price' and 'Number of Rooms'
- 'Price' and 'Floor Level'
- 'Price' and 'Listing Date'
We will also calculate the average cost per square meter in the ten locations with the highest number of listings. Additionally, we will determine the average price for each kilometer in St. Petersburg.

Research Process:

1. Data Quality Assessment: Using the data from the /datasets/real_estate_data.csv file, the first step is to assess the data quality.
2. Data Preprocessing: This involves correcting errors, filling in missing values, or removing anomalous data to enhance data quality.
3. Additional Column Addition: Create additional columns for research purposes.
4. Data Analysis: Analyze the data to identify patterns and relationships. Conclusions: Draw conclusions based on the analysis results.

Used Libraries:

pandas, numpy, matploblib, Jupyter
