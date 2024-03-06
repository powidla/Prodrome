# Prodrome
This repository contains code and results for the experiments in prodrome project using data from migraine patients.
## Content
**Data_preprocessing** folder consists of three notebooks: 
- **data_prep.ipynb** - script to convert original data and extract features into csv.
- **data_prep_conditional.ipynb** - script to convert original data and extract features with timepoint condition.
- **datatata_prep.ipynb** - script to handle json and sql initial commits.

**data_csvs** folder consists of three files: 

- **df_data (1).csv** - original preprocessed dataset.
- **df_data_tp=-2.csv** - dataset with timepoints two points behind.
- **df_data_tp=-3.csv** - dataset with timepoints three points behind.
It was used to train models in first place.  

**ml_code** folder contains saved model and notebooks for experiments.
**figures** folder has results of classification and feature importance results.
