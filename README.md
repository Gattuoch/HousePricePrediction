
- Student name: Gattuoch Chambang Teny
- ID: 1401298
  
# Predicting House Prices 
## Problem statement

As a junior data scientist at real estate company PropertiesInc., I have been tasked with investigating house sales in the King County area and building a model to predict sale price. Key executives are keen to launch an advertising campaign directed towards home owners in that area who might consider selling their house, focusing on higher-end residential properties.

Before building the model, we will address the following descriptive questions through data exploration:

1. Which locations within the King County area have the highest average house prices?

2. Which house attributes increase sale price?

3. Does time of the year have an impact on house sales?
## Technologies/ Packages

* Python version: 3.6.9
* Matplotlib version: 3.1.3
* Seaborn version: 0.9.0
* Pandas version: 0.25.1
* Numpy version: 1.16.5
* Statsmodels version: 0.10.1
* Scikit-learn version: 0.21.2  
* Folium version: 0.9.1 
* Geopandas version: 0.7.0
* Geopy version: 1.21.0 
* Reverse_geocoder version: 1.5.1
* Pickleshare version: 0.7.5 

## Final model details

**Model A**

* 17 features
* Adjusted  R-squared  of 0.701 (70% of variations explained by our model)
* Uses zip code tiers instead of actual zipcodes
* Better for generalising to other areas
* RMSE of 132,444 (mean RMSE with 10-fold cross-validation)

**Model B**

* 87 features
* No interacting terms or polynomials
* Adjusted R-squared  of 0.832 (83% of variations explained by our model)
* RMSE of 99,654 (mean RMSE with 10-fold cross-validation)

**Interpreting Model coefficients**
- A grade 12 house on average is worth USD 52,000 more than grade 11 (model A)
- Being on the waterfront is valued at USD 277,442 (model A)
- For every additional squarefoot of living space, the price inscreases by USD 123.5 (model B)

"# HousePricePrediction1" 
