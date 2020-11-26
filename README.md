# api-challenge

This analysis uses the citipy library to create a random selection of 500+ cities from all around the world.

Using this selection of cities, WeatherMap open API is then used to grab [weather data for each of the cities](https://github.com/lmfao415/Python-API-Challenge/tree/main/WeatherPy).

[Plots](https://github.com/lmfao415/Python-API-Challenge/tree/main/WeatherPy/output_data) were then made to compare the latitude versus the different weather conditions at each location:
Latitude vs. Temperature,
Latitude vs. Humidity,
Latitude vs. Cloudiness,
Latitude vs. Wind Speed,

Linear regression was then ran for these same variables but with the data split between Northern and Southern hemispheres. 

A [heatmap](https://github.com/lmfao415/Python-API-Challenge/tree/main/VacationPy/heatmaps) is made in the [VactionPy](https://github.com/lmfao415/Python-API-Challenge/tree/main/VacationPy) section showing the humidities around the world.
A susbset is then made of cities with desirable conditions to visit, and these cities with hotels are plotted on the heatmap
