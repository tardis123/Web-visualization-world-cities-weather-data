
# Visualization of world cities weather data

This project visualises weather data for about 500 cities on a web site.
Weather data was collected from the OpenWeatherMap web site (https://openweathermap.org/) using an API.

In order to collect world cities a Python module called citypi was used.
Steps to collect world city weather data:

* generate latitude and longitudes
* collect cities using citypi based on latitude/longitude combinations
* use the OpenWeatherMap Current weather data API to collect weather data per city
* generate the following plots:

    * latitude versus temperature
    * latitude versus humidity
    * latitude versus cloudiness
    * latitude versus wind speed

In order to visualize the results, above plots, collected weather data table a web site was built using:

* Bootstrap
* JS Bin

The web site has been built in such a way that it supports using it on mobiles.

You can find the notebook and config.py file used to collect the data and generate the plots in the folder called Sources.
The images used to generate the web site can be found in the folder called images.


**PS In order to run the notebook file (WeatherPy.ipynb) you'll need to apply on OpenWeatherMap for an API key.
   Next, add the API key to the config.py file**
