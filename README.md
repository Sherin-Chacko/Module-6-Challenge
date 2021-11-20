### Module-6-Challenge
World_Weather_Analysis

### 1) OVERVIEW:
The purpose of this project is to collect, analyze and visualize weather data across cities worldwide and to provide travelers with a tool that will allow them to determine their travel destination based on weather conditions.

RESOURCES: 

1. CSV Files: Weather_Database.csv, WeatherPy_vacation.csv

2. Jupyter Notebook Files:: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

3. Python: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals

### 2) WEATHER DATABASE:
A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.

The following data was retrieved from the API call:

  Latitude and longitude,
  Maximum temperature,
  Percent humidity,
  Percent cloudiness,
  Wind speed,
  Current Weather description

### 3) VACATION SEARCH:
Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers on a marker layer-map.

Sample Travel destination:

<img width="1018" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/91294352/142713650-0a61ec33-39cb-4fdd-912c-19f4c42ba735.png">



### 4) VACATION ITINERARY:
Using the Google Directions API, a sample itinerary was created that shows the route between four cities.

<img width="1025" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/91294352/142713598-5765a420-8480-48cc-9652-c14e61fd0a26.png">


