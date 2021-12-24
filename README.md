# WindPowerWeatherML

This project is attempting to use machine learning in order to predict wind power generation based on weather data.

The weather data is collecting from Copernicus. 
Temperature, total precipitation, relative humidity and various wind data points are collected for Chicago, Columbus, Pittsburgh, DC and Philadelphia.
https://cds.climate.copernicus.eu/cdsapp#!/search?type=dataset

The following .ipynb files are for collecting data from the Copernicus API:

city_humid.ipynb \
city_precip.ipynb \
city_temp.ipynb \
city_wind.ipynb 

The data is then saved in the following folders for each city annually or biannually:

complete_wind \
humid_data \
precipitation_data \
temp_data 

The wind power generation data is collected from PJM Interconnection.
https://dataminer2.pjm.com/feed/gen_by_fuel

The annual power generation data is stored in the gen_data folder.

All data was collected and cleaned using the data_collection.ipynb notebook and saved in the following .csv files:

gen_data_full_formatted.csv
weather_data_full.csv

A neural network, random forest regression and XGBoost regression models are compared based on RMSE and MAE evaluation metrics.

The ML_project.ipynb notebook contains the code to run all of the different models that are compared for this project.
