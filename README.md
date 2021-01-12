# python-api-challenge #
## Part I - WeatherPy ##

Visualize the weather of 500+ cities across the world of varying distance from the equator. Accomplishing by using python libraries and the OpenWeatherMap API.

The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
https://github.com/eenabow/python-api-challenge/blob/main/output_data/Fig1.png
* Humidity (%) vs. Latitude
https://github.com/eenabow/python-api-challenge/blob/main/output_data/Fig2.png
* Cloudiness (%) vs. Latitude
https://github.com/eenabow/python-api-challenge/blob/main/output_data/Fig3.png
* Wind Speed (mph) vs. Latitude
https://github.com/eenabow/python-api-challenge/blob/main/output_data/Fig4.png

 <ins>Includes Linear regression on:</ins>

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

**Findings** 
* Latitude vs. Temperature had an interesting negative correlation curve, proving the farther aware from the equator, the colder the climate. 
* The Northern Hemisphere typically has a higher humidity level. 
* As Latitude increases, wind speed increases. 

## Part II - VacationPy ##
Using jupyter-gmaps and the Google Places API for to determine my ideal vacation spot. 


<ins>Includes:</ins>
* A heat map that displays the humidity for every city from Part I.
* Narrowed down dataframe for my ideal vacation weather.
* Heatmap with hotel marker overlays near my ideal Vacation locations.
