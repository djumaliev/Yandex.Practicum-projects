# YP_metallurgy
Yandex Practicum Data Science and Machine Learning Bootcamp: Metallurgy.

In order to optimize production costs, the metallurgical plant "Steel Bird" has decided to reduce electricity consumption during the steel processing stage. To achieve this, the plant needs to control the temperature of the alloy. Our task is to build a model that will predict this temperature. The customer wants to use the developed model for simulating the technological process. Below, we will provide details of this process. It is important to know them before generating new features.

# Processing Stage Description
Steel is processed in a metallic crucible with a capacity of about 100 tons. To withstand high temperatures, the crucible is lined with refractory bricks on the inside. Molten steel is poured into the crucible and heated to the required temperature using graphite electrodes installed in the crucible's lid.

Sulfur is removed from the alloy (this process is desulfurization), the chemical composition is adjusted by adding impurities, and samples are taken. Steel is alloyed—its composition is altered—by introducing pieces of the alloy from a bunker for bulk materials or wire through a special tribe apparatus (from the English "tribe" meaning "mass").

Before introducing alloying additives for the first time, the temperature of the steel is measured, and its chemical analysis is performed. The temperature is then raised for a few minutes, alloying materials are added, and the alloy is blown with inert gas. It is then stirred, and measurements are taken again. This cycle is repeated until the target chemical composition and optimal melting temperature are achieved.

The molten steel is then sent for metal finishing or enters the continuous casting machine. The final product emerges from there in the form of slabs.

Data Description:

The data consists of several files obtained from different sources:

- data_arc_new.csv — data about electrodes;
- data_bulk_new.csv — data about the supply of bulk materials (volume);
- data_bulk_time_new.csv — data about the supply of bulk materials (time);
- data_gas_new.csv — data about blowing the alloy with gas;
- data_temp_new.csv — results of temperature measurements;
- data_wire_new.csv — data about wire materials (volume);
- data_wire_time_new.csv — data about wire materials (time).

File data_arc_new.csv

- key — batch number;
- Start of arc heating — start time of arc heating;
- End of arc heating — end time of arc heating;
- Active power — active power value;
- Reactive power — reactive power value.

File data_bulk_new.csv

- key — batch number;
- Bulk 1 … Bulk 15 — volume of the supplied material.

File data_bulk_time_new.csv

- key — batch number;
- Bulk 1 … Bulk 15 — time of material supply.

File data_gas_new.csv

- key — batch number;
- Gas 1 — volume of the supplied gas.

File data_temp_new.csv

- key — batch number;
- Measurement time — measurement time;
- Temperature — temperature value.

File data_wire_new.csv

- key — batch number;
- Wire 1 … Wire 15 — volume of the supplied wire materials.

File data_wire_time_new.csv

- key — batch number;
- Wire 1 … Wire 15 — time of wire material supply.

In all files, the 'key' column contains the batch number. There may be multiple rows with the same key value in the files, corresponding to different processing iterations.

# Work Plan

- Step 1. Data Loading

Load the data and perform an initial exploration.

- Step 2. Exploratory Data Analysis and Data Preprocessing

Conduct exploratory analysis for each dataframe and preprocess if necessary. Draw conclusions about the features: whether they are needed for model training.

- Step 3. Data Integration

Combine selected features into one dataframe using a key.

- Step 4. Exploratory Data Analysis and Preprocessing of the Merged Dataframe

Perform exploratory analysis on the merged dataframe, visualize feature distributions, and preprocess if necessary. Conduct a correlation analysis. New features may be generated if needed.

- Step 5. Data Preparation

Prepare the data for model training. Split the data into two sets, considering the data and model characteristics during scaling and encoding.

- Step 6. Machine Learning Model Training

Train three models: Linear Regression, Random Forest, and CatBoost. Tune optimal hyperparameters for each.

- Step 7. Selecting the Best Model

Choose the best model and evaluate its performance on the test set.

- Step 8. Overall Conclusion and Recommendations to the Customer

Provide an overall conclusion about the work done, describe the main stages, present the results obtained, and offer business recommendations.

Used lybraries: pandas, numpy, matplotlib, seaborn, sklearn, catboost(1.0.3), tqdm, os
