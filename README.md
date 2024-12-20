# STAT 447 Project: Airbnb Dataset Analysis

## Overview

This project serves to conduct a general analysis of Airbnb data sourced from InsideAirbnb as well as 2 other datasets related to Crime or Income. We are looking to create models to predicted either price/estimated number of bookings and build a classification model for whether a host is a superhost. We also make use of Feature Engineering techniques in hopes of adding useful predictor variables using the non-numerical/non-categorical columns from the datasets. An example of this is using the text from airbnb reviews to create an average review sentiment metric for listings.

## Datasets

The InsideAirbnb was accessed at <https://insideairbnb.com/get-the-data/>  
The data used was from New York City for the months May through September, we used the `listings.csv` and `reviews.csv` datasets from each month for the purposes of the analysis.  
License for InsideAirbnb Data : [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)

## Repository Index

`Datasets` : Directory containing the datasets, inside there is a sub-directory for the Airbnb listings data, the Airbnb Reviews data is not uploaded to the repository as the file size is too large.  
`PreProcessingAirbnb.ipynb` : Notebook that serves to combine, clean and preprocess the `listings.csv` datasets from InsideAirbnb.  
`FeatureEngineeringAirbnb.ipynb`: Notebook that does Feature Engineering based on the text-based columns (such as reviews & descriptions) as well as converting other columns (such as amenities & host verifications) to categorical variables.  
`EdaAirbnb.ipynb` : Notebook for exploratory Data Analysis of the primary Airbnb Dataset.    
`EdaCrime.ipynb`: Notebook for exploratory Data Analysis of supplementary Crime Dataset.  
`EdaIncome.ipynb`: Notebook for exploratory Data Analysis of supplementary Income Dataset.  
`airbnb_map.html` & `crimemap.html`: 2 html files for interactive maps created during the EDA of our datasets, help visualize the distribution of types of rooms across NYC and the distribution of crimes across NYC.  
`Modeling.ipnb`: Modeling Work for just predicting whether the host is a superhost.     
`ModelingNumBookings.ipynb`: Modeling Work for predicting the number of bookings listings will receive.  
