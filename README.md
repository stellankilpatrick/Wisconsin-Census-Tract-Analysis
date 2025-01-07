# Wisconsin Census Tract Analysis

<img src="https://www.sco.wisc.edu/wp-content/uploads/2021/05/wi-county-plss-boundaries-final.jpg" alt="Visualization of Land Use" width="300">

## Project Overview
This project analyzes census tract and county data of Wisconsin to study the relationship and correlation between types of land use and population. GeoJSON data will be read, cleaned, and analyzed. A **K-means clustering** algorithm is used to decipher the different types of counties located throughout the state based on their land use (developed, crops, forest, etc.). Finally, a **linear regression model** will be trained to predict the population of any area based on the type of land contained within.
This project uses Python libraries such as **scikit-learn**, **Rasterio**, **GeoPandas**, and **SQLite**, and is implemented within a **Jupyter Notebook** environment.

## Data Sources
All data was accessed through and provided by the course COMP SCI 320 at the University of Wisconsin-Madison. The original data source is unknown, though assumed to be public census data found on census.gov.
