What's the Weather Like?

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?

![Equator](Images/equatorsign.png)

## WeatherPy

In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

Your objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Your final notebook must:

* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed with the city number and city name.
* Save both a CSV of all data retrieved and png images for each scatter plot.

As final considerations:

* You must complete your analysis using a Jupyter notebook.
* You must use the Matplotlib or Pandas plotting libraries.
* You must include a written description of three observable trends based on the data.
* You must use proper labeling of your plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.
* See [Example Solution](WeatherPy_Example.pdf) for a reference on expected format.

### Analysis
* As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude). More interestingly, however, is the fact that the southern hemisphere tends to be warmer this time of year than the northern hemisphere. This may be due to the tilt of the earth.
* There is no strong relationship between latitude and cloudiness. However, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.
* There is no strong relationship between latitude and wind speed. However, in northern hemispheres there is a flurry of cities with over 20 mph of wind.

### Observable Trends
* Collecting weather data from random and diverse cities around the world using the OpenWeatherMap API,the data illustrated maximum temperature(in Fahrenheit),humidity(%),cloudiness(%)and wind speed(in mph)with the corresponding city,and with respect to the geo-coordinate,Latitude.
* There seems to be little to no correlation between humidity and Latitude as well as with cloudiness and Latitude. The scatter plot visualizations display a considerable amount of heterogeneity even at similar Latitudes.
* Finally, wind speeds increase in the upper and lower halves on the hemisphere.
* As the correlation coeffient and linear regression model shows a strong negative correlation between latitude and northern hemisphere. Moreover,in southern hemisphere the correlation coefficient and linear regression model shows a positive correlation between latitude and maximum temperature.
* And the correlation coefficent and linear regression model for humidity vs latitude shows a weak positive correlation for both hemispheres.
* The correlation coefficient and linear regression model show a weak positive correlation between cloudiness and latitude in the northern hemisphere and weak positive correlation in the southern hemisphere.
* The correlation coefficient and linear regression model show a weak positive correlation between wind speed(mph) and latitude in the northern hemisphere and shows an almost moderate negative correlation between wind speed(mph) and latitude in the southern hemisphere.



