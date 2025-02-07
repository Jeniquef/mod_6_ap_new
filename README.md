### WeatherPy and VacationPy Project

## Overview

 The project is divided into two main parts: WeatherPy and VacationPy, utilizing Python, Jupyter Notebook, APIs, and data visualization techniques.

## Part 1: WeatherPy

WeatherPy involves analyzing and visualizing weather conditions for over 500 cities worldwide. 

# Requirements:

- Retrieving Weather Data

- The citipy library is used to generate random geographic coordinates and find the nearest cities.

- Weather data, including temperature, humidity, wind speed, and cloudiness, is retrieved using the OpenWeatherMap API.

# Creating Scatter Plots

- Scatter plots are generated to visualize the following relationships:

* Latitude vs. Temperature

* Latitude vs. Humidity

* Latitude vs. Cloudiness

* Latitude vs. Wind Speed

# Performing Linear Regression

Linear regression is computed and visualized for each weather parameter separately for the Northern and Southern Hemispheres.

The regression line, equation, and r-squared value are included in the plots.

Results are analyzed to understand trends and correlations.

## Part 2: VacationPy

- VacationPy utilizes weather data to identify ideal vacation spots and locate nearby hotels.

- Humidity is represented as the size of each point on the map.

- Filtering Ideal Locations

- The dataset is narrowed down based on the choosen criteria

- Finding Nearby Hotels

- Geoapify API is used to locate hotels of selected city coordinates.

- Hotel names, cities, and countries are stored in a DataFrame.

- Hotel locations are displayed on a map with hover messages containing hotel and city details.
