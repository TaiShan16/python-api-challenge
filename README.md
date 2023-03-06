# python-api-challenge

Part 1: WeatherPy

This part, we use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code, which generated about 600 cities of varying distances from the equator. Then, we create a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Next step, we computed the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).


Part 2: VacationPy

In this part, we use weather data of various cities from WeatherPy part to plan future vacations. We use the Geoapify API and the geoViews Python library to create map visualizations of those cities. Then we create python script to narrow down the cities in the dataframe to find our ideal weather condition. After the ideal weather condition was select, we then use the Geoapify API to find  the first hotel located within 10,000 metres of our coordinates, and add the hotel name and country as additional information in the hover message for each city in the map.
