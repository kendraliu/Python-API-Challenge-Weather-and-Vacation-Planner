# Python Api Challenge: Weather and Vacation Planner

## Overview
The Weather and Vacation Planner project consists of two parts. The first part of the project aims to provide evidence of the correlation (or non-correlation) between the latitude of a location and its weather variables, including temperature, humidity, cloudiness, and wind speed. Over 500 cities are generated randomly to provide enough data points. Weather information is gathered from the [OpenWeatherMap API](https://openweathermap.org/api) Scatter plots and correlation analyses are generated to gain insights into the relationship between latitude and weather.

The second part of the project utilizes the data from the first part to identify cities with desirable weather conditions for potential vacations. The project identifies the nearest hotels to these cities using the [Geoapify API](https://apidocs.geoapify.com/). A map is created to visualize the locations of the selected cities and their corresponding hotels.
![Vacation spots city information with nearest hotel](/Output Data/vacationSpotsHoveringOver.png)

## Files
* /WeatherPy.ipynb: Contains the first part of the project, analyzing the relationship between latitude and weather variables
* /Output Data/: Directory containing scatter plots generated in /WeatherPy.ipynb
* /VacationPy.ipynb: Contains the second part of the project, filtering cities for potential vacations and visualizing them on a map. A larger size of the markeers indicates higher humidity of the city.