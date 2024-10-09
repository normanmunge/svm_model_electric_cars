# ELECTRIC CARS PREDICTION - Estimating the price of cars in the Washington Area

This dataset contains information on the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) that are currently registered with the Washington State Department of Licensing (DOL).

The colums in the dataset include:
* VIN (1-10) - The 1st 10 characters of each vehicle's Vehicle Identification Number (VIN).
* County- The county in which the registered owner resides.
* City - The city in which the registered owner resides.
* State- The state in which the registered owner resides.
* ZIP Code - The 5-digit zip code in which the registered owner resides.
* Model Year - The model year of the vehicle is determined by decoding the Vehicle Identification Number (VIN).
* Make- The manufacturer of the vehicle, determined by decoding the Vehicle Identification Number (VIN).
* Model- The model of the vehicle is determined by decoding the Vehicle Identification Number (VIN).
* Electric Vehicle Type - This distinguishes the vehicle as all-electric or a plug-in hybrid.
* Clean Alternative Fuel Vehicle (CAFV) Eligibility - This categorizes vehicles as Clean Alternative Fuel Vehicles (CAFVs) based on the fuel requirement and electric-only range requirement.
* Electric Range - Describes how far a vehicle can travel purely on its electric charge.
* Base MSRP - This is the lowest Manufacturer's Suggested Retail Price (MSRP) for any trim level of the model in question.
* Legislative District - The specific section of Washington State that the vehicle's owner resides in, as represented in the state legislature.
* DOL Vehicle ID - Unique number assigned to each vehicle by the Department of Licensing for identification purposes.
* Vehicle Location - The center of the ZIP Code for the registered vehicle.
* Electric Utility - This is the electric power retail service territory serving the address of the registered vehicle.
* Expected Price - This is the expected price of the vehicle.

## Objective & Goal
Thus, the objective is to build and train a Support Vector Model (SVM) ML model to predict the estimated price of a particular vehicle.
This project is ideal for data scientists enthusiasts and anyone interested in learning how to train and evaluate a SVM Regressor model.

## Steps to follow
* Import libraries
* Load dataset
* Data wrangling & exploration - statistical analysis, data cleaning, exploration, visualization, checking outliers etc
* Feature engineering & selection - standardizing the features
* Training model
* Making predictions
* Evaluation of the model
