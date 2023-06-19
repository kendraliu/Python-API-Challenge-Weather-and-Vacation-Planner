# python-api-challenge

## Overview
The first part of the project aims to provide evidence of the correlation (or non-correlation) between the latitude of a location and its weather, targeting the location's temperature, humidity, cloudiness, and wind speed. Over 500 cities are generated randomly to provide enough data points. Weather information is gathered from [OpenWeatherMap API](https://openweathermap.org/api) Scatter plots and correlation analyses are produced for the understanding of the inference.

The second part of the projec uses the data from part 1 and picks out cities that have nice weather for potential vacations and provides the names of the nearest hotels. It finds the nearest hotel using [Geoapify API](https://apidocs.geoapify.com/). 
A map is created for the visualization of this information.

## Files
* /WeatherPy.ipynb: first part of the project, analyzes the relationship between latitude and weather variables 
* /Output Data/: contains scatter plots generated in /WeatherPy.ipynb
* /VacationPy.ipynb: second part of the project, filters the cities for a possible vacation, and marking them on a map to visualize it