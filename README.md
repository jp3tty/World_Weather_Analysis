# World_Weather_Analysis
## Overview
The purpose of this project is to help with vacation planning, and impact the overall travel experience by collecting weather data across cities worldwide to provide travelers with a tool allowing them to select their travel destinations based on the locations weather conditions. The tool, an application, is designed to couple weather information to city locations, providing the user with a large number of place to choose to travel.

## Weather Database
For weather information, cities around the world were located by randomly generating global coordinates and using a python module to the nearest corresponding city. Each cities weather information was obtain from the OpenWeatherMap API to gather the following data:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current weather description

## Vacation Application
identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers showing

* Hotel name
* City
* Country
* Current weather
* Max Temperature

![WeatherPy_Vacation](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Sample Itinerary
A trip to Brazil was planned to demonstrate the apps functionality. Using the Google Directions API, a sample itinerary was created that shows the route between four cities in Brasil.

![Brasil Directions](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

![Brasil Hotel Information](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)