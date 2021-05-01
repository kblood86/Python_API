# Python_API

This assignment has two parts. Part one looks at cities and their weather based on their location. Part two expands on part one and determines the best vacation spot of these locations and where to stay! 


Weather PY

This section starts by selecting 1500 unique cities based on their latitude and longitude. Then, using an API call, it performs a weather check on the cities selected. A series of scatter plots are created to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

!!!!!!!After each plot, add a sentence or two explaining what the code is analyzing.

Then the cities are sorted into their respective hemisphere and a linear regression is run on the following relationships: 

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


Vacation Py

This section starts by creating a heat map based on the humidities found for each city in part one.

The cities are then narrowed down to find the ideal weather condition:

  * A max temperature lower than 80 degrees but higher than 70 degrees.

  * Wind speed less than 10 mph.

  * Zero cloudiness.


Google Places API is then used to find the first hotel for each city located within 5000 meters of your coordinates.

These hotels are plotted the hotels on top of the humidity heatmap. The pin includes the Hotel name, City and Country. 

