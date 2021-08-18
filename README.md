# Predicting Chronic Kidney Disease (CKD)
Models to predict the onset of chronic kidney disease (CKD)

## What are included
* Raw data consist of 300 patients, with longitudinal medical record up to 1429 days from baseline
* A PDF is available to present the methods and results
* “CSV” folder contain all the raw data and processed data
* “figures” folder contain all the ROC curve
* “models” folder contain all the optimized models
* “predictions” folder contain all the prediction result for model comparison

# How to use the notebooks
* exploreData.ipynb is to look through distribution of values
* Run prepareData.ipynb to prepare data for modelling

## “Raw” values
* Run Modelling_daybin.ipynb for prediction results of the 180-day bin data
* Run Modelling_agg.ipynb for prediction results of the Aggregated data
* Run Modelling_temporal.ipynb for prediction results of the Temporal data

## Categorized (including categorization of drugs by treatment)
* Run Modelling_daybin_cat.ipynb for prediction results of the 180-day bin data
* Run Modelling_agg_cat.ipynb for prediction results of the Aggregated data
* Run Modelling_temporal_cat.ipynb for prediction results of the Temporal data

## GFR
* Run Modelling_gfr.ipynb for prediction results of the GFR data
