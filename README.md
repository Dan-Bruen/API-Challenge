# API-Challenge
## WeatherPy

In this case study, I will be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I will be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

My objective is to build a series of scatter plots to showcase the following relationships:

 1. Temperature (F) vs. Latitude
 2. Humidity (%) vs. Latitude
 3. Cloudiness (%) vs. Latitude
 4. Wind Speed (mph) vs. Latitude

My final notebook will:

 1. Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
 2. Perform a weather check on each of the cities using a series of successive API calls.
 3. Include a print log of each city as it's being processed with the city number and city name.
 4. Save both a CSV of all data retrieved and png images for each scatter plot.
