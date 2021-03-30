# DSAI-Mini-Project

NTU School of Computer Science and Engineering (AY2019/20 S2)
CZ1015 Introduction to Data Science & Artificial Intelligence

### Introduction
Dataset: https://www.kaggle.com/airbnb/seattle

Problem Statement: What are the factors that make a listing more expensive?

Problem: Regression

Regression Models Performed:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest Regress
  - XGBoost 
  - CatBoost

### Summary: Exploratory Analysis
Broken into 3 sub-problems:
1. What property/room types and facilities affect its price?
2. Are there particular locations in Seattle where AirBnB listings fetch higher prices?
3. Does textual data in the summary and sentiments of reviews affect price?

### Summary: Regression Models
- Model best at predicting price: Random Forest Regression
- Use TreeInterpreter to decompose the prediction into a sum of contributions from each feature

### Conclusion
Factors that increase price (Explorary Analysis):
- Listing an entire property (instead of single room)
- Include words like 'view', 'modern' & 'walk' in the summary of the listing
- Having amenities such as Washer, Dryer, Heating, Wireless Internet, Smoke Detector, Free Parking, Kid Friendly & TV
- Have the location of the listing be in Belltown or West Queen Anne

Factors that increase price (Regression Modelling):
- Listings that are apartments
- Listings that have ideally 6 bedrooms
- Having amenities such as Hot tub, Sauna, Pool, Gyms or Elevators
