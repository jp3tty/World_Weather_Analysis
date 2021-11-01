# World_Weather_Analysis
## Overview
The purpose of this project is to help with vacation planning and impact the overall travel experience by collecting weather data from cities worldwide, providing travelers with a tool aiding them to select their travel destinations based on their ideal weather conditions. The tool, an application, is designed to couple weather information to city locations, providing the user with a large number of place to choose to travel. It also provides hotel information for each city and can road routes when planning a multi-city trip.

## Weather Database
Weather information, sourced from the OpenWeatherMap API, was gathered by generating 2000 random global coordinates and then tying those coordinates to their nearest cities. The following information was gathered for each city:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current weather description

## Vacation Application
Temperature preferences (hottest and coldest daily temp.) are used for the traveler to identify their destination. Once input the application displays a world map showing pins of potential destinations.

![WeatherPy_Vacation](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

The map showcases destinations using pop-up markers showing

* Hotel name
* City
* Country
* Current weather
* Max Temperature


## Sample Itinerary
A trip to Brazil was planned to demonstrate the apps functionality. Using the Google Directions API, a sample itinerary was created that shows the route between four cities in Brasil.

![Brasil Directions](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

![Brasil Hotel Information](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)