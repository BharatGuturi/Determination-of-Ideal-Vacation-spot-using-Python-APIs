# Determination-of-Ideal-Vacation-spot-using-Python-APIs
This project deals with the determination of possible locations for vacations based on the required parameters. Python requests, APIs and JSON traversals have been done to determine the possible locations for vacations around the world. 

# Summary
Based on the retrieved data, various plots such as Latitude vs Temperature, Latitude vs Humidity, Latitude vs Cloudiness and Latitude vs Wind Speed have been plotted to analyse for the ideal location of vacation. Ideal temperature and wind speed range is selected to narrow down the search. Based on the obtained city data, nearest hotels are determined.

# Instructions

1)  To run the repo, use the following command:
    git clone https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs.git
    
2)  Generate the api keys for OpenWeatherMaps using the url: https://home.openweathermap.org/api_keys. Please ensure that an account is created in https://openweathermap.org/ prior to accessing the api keys.

3)  The api keys should be named as "api_keys.py" and the api should be assigned to "weather_api_key" inside the file. The api_keys.py file should be placed inside "WeatherPy" folder.

4)  Generate the api keys for google maps prior to executing the files.

5)  The api keys for google maps should be named as "api_keys.py" and the api should be assigned to "g_key" inside the file. The api_keys.py file should be placed inside "VacationPy" folder.

6)  Execute the python file "WeatherPy.ipynb" inside the folder "WeatherPy". "weather_data.csv" is the csv generated while executing the file and will be used as input for "VacationPy.ipynb"

7)  Execute the python file "VacationPy.ipynb" inside the folder "VacationPy"

8)  "Output Data" in each folder consists of snips of the final graphs.

# Data Analysis Outputs

## Latitude vs Max Temperature Plot

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/LatitudevsMaxTemp.png' width = 80% ></p> 

## Latitude vs Min Temperature Plot

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/LatitudevsMinTemp.png' width = 80% ></p> 

## Latitude vs Temperature Plot

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/LatitudevsTemp.png' width = 80% ></p>

## Latitude vs Humidity Plot

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/LatitudevsHumidity.png' width = 80% ></p>

## Latitude vs Cloudiness Plot

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/LatitudevsCloudiness.png' width = 80% ></p>

## Latitude vs Wind Speed Plot

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/LatitudevsWindSpeed.png' width = 80% ></p>

## Latitude vs Max Temp Linear Regression in Northern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/NorthLatitudevsMaxTempNorth.png' width = 80% ></p>

## Latitude vs Max Temp Linear Regression in Southern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/SouthLatitudevsMaxTempSouth.png' width = 80% ></p>

## Latitude vs Humidity Linear Regression in Northern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/NorthLatitudevsHumidityNorth.png' width = 80% ></p>

## Latitude vs Humidity Linear Regression in Southern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/SouthLatitudevsHumiditySouth.png' width = 80% ></p>

## Latitude vs Cloudiness Linear Regression in Northern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/NorthLatitudevsCloudinessNorth.png' width = 80% ></p>

## Latitude vs Cloudiness Linear Regression in Southern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/SouthLatitudevsCloudinessSouth.png' width = 80% ></p>

## Latitude vs Wind Speed Linear Regression in Northern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/NorthLatitudevsWindSpeedNorth.png' width = 80% ></p>

## Latitude vs Wind Speed Linear Regression in Southern Hemisphere

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/SouthLatitudevsWindSpeedSouth.png' width = 80% ></p>

## Heatmap showing humidity of various locations

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/HeatmapHumidity.png' width = 80% ></p>

## Heatmap showing probable vacation locations based on few parameters

<p align="center"><img src='https://github.com/BharatGuturi/Determination-of-Ideal-Vacation-spot-using-Python-APIs/blob/main/Output/HeatmapVacationLocation.png' width = 80% ></p>


