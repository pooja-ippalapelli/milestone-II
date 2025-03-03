# Milestone 2 Project: Predicting Airbnb Listing Prices

This repository contains notebooks and data for our Milestone 2 Project aimed at predicting Airbnb listing prices.

## Main Notebooks

1. **Combine_data.ipynb**  
   Used to combine and clean listing and amenities data to create `Combined_data_v1.csv`, which serves as the input for the subsequent notebooks. - not all files to run this ipynb are present in this git repo

2. **Final_Unsupervised_learning.ipynb**  
   Contains all the unsupervised learning analysis performed on the data.

3. **supervised_models.ipynb**  
   Initial modeling to predict Airbnb listing prices.

4. **hyperparameter_sensitivity.ipynb**  
   Hyperparameter tuning of the supervised models.

5. **ablation_testing.ipynb**  
   Ablation testing of supervised models to evaluate feature importance and model performance.

## Extra Notebooks (Exploratory Analysis)

A set of extra notebooks is included that explores amenities and facilities. While a lot of this data was not ultimately used in the final project, these notebooks provide insights into the steps taken to explore them. Please note that due to the size of the datasets, some of the data inputs are not present.

1. **amenities_explorations_jacob.ipynb**  
   Explores individual amenities and generates the `amenities_presence_absence.csv` file.

2. **Facilites_Data_Cleaning_v2.ipynb**  
   Explores the facilities data through cluster evaluation.

3. **popularity_score_aggregation.ipynb**  
   Creates the `listing_booking_info.csv` file, which contains booking ratios for the listings.
