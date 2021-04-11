# api-challenge

This analysis uses the citipy library to create a random selection of 500+ cities from all around the world.

Using this selection of cities, WeatherMap open API is then used to grab weather data for each of the cities in the [WeatherPy](https://github.com/lmfao415/Python-API-Challenge/tree/main/WeatherPy) part of the analysis. This whole process can be seen in the WeatherPy [Jupyter Notebook](https://github.com/lmfao415/Python-API-Challenge/blob/main/WeatherPy/WeatherPy.ipynb). 

In addition to the combined city and weather data saved to [cities.csv](https://github.com/lmfao415/Python-API-Challenge/blob/main/WeatherPy/output_data/cities.csv), the WeatherPy notebook additionally creates plots  in the [output_data](https://github.com/lmfao415/Python-API-Challenge/tree/main/WeatherPy/output_data) folder to compare latitude versus the different weather conditions at each location:
Latitude vs. Temperature,
Latitude vs. Humidity,
Latitude vs. Cloudiness,
and Latitude vs. Wind Speed.

For example, here is the plot showing temperature versus latitude:

![sample](https://github.com/lmfao415/Python-API-Challenge/blob/main/WeatherPy/output_data/Lat_vs_Temp.png?raw=true) 

Linear regression was then ran for these same variables but with the data split between Northern and Southern hemispheres. 
Shown here is the temperature by latitude for the Northern hemisphere:

![sample](https://github.com/lmfao415/Python-API-Challenge/blob/main/WeatherPy/output_data/NorthLat_vs_Temp.png?raw=true)

Subsequently, in the [VactionPy](https://github.com/lmfao415/Python-API-Challenge/tree/main/VacationPy) section, [heatmaps(https://github.com/lmfao415/Python-API-Challenge/tree/main/VacationPy/heatmaps) are mased on global humidity data gathered in the WeatherPy process.

A susbset is then made of cities with desirable conditions to visit, and these cities with hotels are plotted on the heatmap
