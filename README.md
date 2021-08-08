# Time-Series-Forecasting-of-temperature-data

- Worked on finding a correlation between the air temperature and water temperature of the river Ganga, that flows through the city of Varanasi mainly in two sections: through the populated part of the city and through the non populated one.

- Derived the minimum, maximum and mean temperatures of the two sections (on Google Earth Engine editor) using the 'ERA-5 daily aggregates' dataset on the shapefiles that were created on QGIS.

- With the seasonal dataset obtained above, Machine Learning models such as ARIMA and Prophet were built to predict both the temperatures in the two sections for the upcoming years while also deriving the mathematical correlation between them.

- Additionally, for river temperature, LSTM based CNN hybrid models were implemented to obtain the predictions in the form of raster data/geospatial output.
