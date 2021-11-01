# World_Weather_Analysis
## Overview
The purpose of this project is to help with vacation planning and impact the overall travel experience by collecting weather data from cities worldwide, providing travelers with a tool to select ideal travel destinations based on weather conditions. The tool, an application, is designed to couple weather information to city locations, giving the user a large number of choices. It also provides hotel information for each city and can plan road routes for ground travel, when planning a multi-city trip.

## Weather Database
Weather information, sourced from the OpenWeatherMap API, was gathered by generating 2000 random global coordinates and then tying those coordinates to their nearest cities. The travel application gathers the following data for each city:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current weather description

## Vacation Itinerary
The application begins with the travelers temperature preferences (hottest and coldest daily temp.) to identify destinations. Once input, a world map with pins of potential destinations is diplayed:

![WeatherPy_Vacation](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

The map above highlights cities with a maximum temperature between 70 and 85 degress Fahrenheit. Selecting a pin provides the application user with:

* Hotel name
* City
* Country
* Current weather
* Max Temp.

The Hotel names are sourced from the Google Places API.

## Sample Itinerary
Below is a sample trip to Brazil to demonstrate the applications functionality. Four cities have been selected as our destinations:

* Arraial Do Cabo
* Praia Grande
* Ribas Do Rio Pardo
* Jatai

and a road route (utilizing Google Directions API) between them is provided for ground travel.

![Brasil Directions](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

Selecting each pin will pop-up:

* Hotel name
* City
* Country
* Max Temp.

![Brasil Hotel Information](https://github.com/jp3tty/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)