# World_Weather_Analysis

## Overview
In this assignment, I will analyze, visualize, and use statistical skills by retrieving and analyzing weather data for a hypothetical travel company. This example will show  knowledge of Python, decision and repetition statements, data structures, Pandas, Matplotlib, and Google Maps API.


## Basic Project Plan
Here's an outline of the project plan:

- **Task:** Collect and analyze weather data across cities worldwide.
- **Purpose:** PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
- **Method:** Create a Pandas DataFrame with 2000 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

The analysis of the data will be split into two main parts, or stages.

1. **Collect the Data**

- Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
- Use the citipy module to list the nearest city to the latitudes and longitudes.
- Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
- Parse the JSON data from the API request.
- Collect the following data from the JSON file and add it to a DataFrame:
    - City, country, and date
    - Latitude and longitude
    - Maximum temperature
    - Humidity
    - Cloudiness
    - Wind speed
    - Weather description


2. **Visualize Travel Data**

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

- Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
- Create a heatmap for the new DataFrame.
- Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
- Add pop-up markers to the heatmap that display information about the city, weather description, current maximum temperature, and a hotel in the city.
- From the list of potential travel destinations, choose four cities to create a travel itinerary. 
- Using the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.