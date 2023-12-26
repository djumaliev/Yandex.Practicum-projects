# YP_recovery_of_gold_from_ore
Yandex Practicum Data Science and Machine Learning Bootcamp: Recovery of gold from ore.

Prepare a prototype of a machine learning model for "Digits". The company develops solutions for the efficient operation of industrial enterprises.

The model should predict the gold recovery coefficient from gold-bearing ore. Use data with parameters of extraction and purification.

The model will help optimize production to avoid launching a facility with unprofitable characteristics.

We need to:

- Prepare the data;
- Conduct exploratory data analysis;
- Build and train the model.

- Research process:
  - Open the data files with the following paths: 'gold_industry_train.csv', 'gold_industry_test.csv', 'gold_industry_full.csv'.
  - The data is indexed by the date and time of information acquisition (feature: date). Parameters obtained at close times are often similar.
  - The dataset 'gold_industry_full.csv' contains both training and test sets. Conduct analysis and data preprocessing if necessary. Verify the formula for calculating the enrichment efficiency. Analyze features not available in the test set.

- Preprocess the data.

  - Examine the changes in the concentration of elements at each stage.
  - Analyze the distribution of particle sizes in the training and test sets.
  - Investigate total concentrations.
  - Build a prediction model.
  - Write a function to calculate the final sMAPE.
  - Train and test several models.
  - Choose the best model and assess its quality on the test set.
  - The data should adhere to the following parameters:

- Technological process:

  - Rougher feed — initial raw material.
  - Rougher additions (or reagent additions) — flotation reagents: Xanthate, Sulphate, Depressant.
  - Xanthate — xanthate (promoter or flotation activator).
  - Sulphate — sulfate (sodium sulfide in this production).
  - Depressant — depressant (sodium silicate).
  - Rougher process — flotation.
  - Rougher tails — tailings.
  - Float banks — flotation unit.
  - Cleaner process — cleaning.
  - Rougher Au — rough gold concentrate.
  - Final Au — final gold concentrate.

- Stage parameters:

  - air amount — air volume.
  - fluid levels — liquid level.
  - feed size — feed particle size.
  - feed rate — feed rate.

- Feature names should be in the format:

  - [stage].[parameter_type].[parameter_name]
  - Example: rougher.input.feed_ag

- Possible values for the [stage] block:

  - rougher — flotation.
  - primary_cleaner — primary cleaning.
  - secondary_cleaner — secondary cleaning.
  - final — final characteristics.

Possible values for the [parameter_type] block:

  - input — raw material parameters.
  - output — product parameters.
  - state — parameters characterizing the current stage state.
  - calculation — calculated characteristics.

Used lybraries:
pandas, matplotlib, numpy, seaborn, sklearn, os
