# WindPowerWeatherML

This project is attempting to use machine learning in order to predict wind power generation based on weather data.

The weather data is collecting from Copernicus. 
Temperature, total precipitation, relative humidity and various wind data points are collected for Chicago, Columbus, Pittsburgh, DC and Philadelphia.
https://cds.climate.copernicus.eu/cdsapp#!/search?type=dataset

The wind power generation data is collected from PJM Interconnection.
https://dataminer2.pjm.com/feed/gen_by_fuel

A neural network, random forest regression and XGBoost regression models are compared based on RMSE and MAE evaluation metrics.
