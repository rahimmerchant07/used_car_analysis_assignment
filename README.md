# What Drives the Price of a Car?

# Overview

This project analyzes a dataset of used vehicle listings to determine which factors have the biggest impact on vehicle prices. The CRISP-DM framework was used throughout the project to guide the business understanding, data preparation, modeling, and evaluation process. The goal of the analysis is to help used car dealerships better understand what customers value when purchasing used vehicles and support better inventory and pricing decisions.

# Business Problem

Used car dealerships need to make informed decisions about:
- which vehicles to purchase
- how to price inventory
- which vehicle features are most valuable to customers

This project explores how factors such as mileage, condition, manufacturer, and model year influence resale value.


# Dataset

The dataset contains over 400,000 used vehicle listings and includes features such as:
- price
- year
- manufacturer
- condition
- fuel type
- odometer
- transmission
- title status
- vehicle type

# Models Used

The following regression models were used:
- Linear Regression
- Ridge Regression
- Lasso Regression
- GridSearchCV
- Cross-validation


# Key Findings

- Lower mileage vehicles generally have higher resale value
- Vehicle condition has a strong impact on pricing
- Luxury manufacturers tend to maintain higher resale prices
- Newer vehicles are typically priced higher than older vehicles
- Regularized regression models helped improve model stability and reduce overfitting


# Notebook
https://github.com/rahimmerchant07/used_car_analysis_assignment/blob/main/used_car_analysis_assignment.ipynb
