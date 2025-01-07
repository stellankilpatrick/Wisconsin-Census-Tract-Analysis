# Wisconsin-Census-Tract-Analysis
## Project Overview
This project analyzes census tract and county data of Wisconsin to study the relationship and correlation between types of land use and population. geojson data will be read in, cleaned, and analyzed. K-means clustering is used to decifer the different types of counties located throughout the state based on their land use (developed, crops, forest, etc.). Finally, a linear regression model will be trained to predict the population of any area based on the type of land contained within.

This project uses Python libraries such as scikit-learn, Rasterio, geopandas, and SQLite.

## Data Sources
All data was accessed through and provided by the course COMP SCI 320 at the University of Wisconsin-Madison. The original data source is unknown, though assumed to be public census data found on census.gov.
