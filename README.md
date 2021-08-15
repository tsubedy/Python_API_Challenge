# Python_API_Challenge


In this challenge, Python script is created to visualize the weather of 500+ cities across the world of varying distance from the equator usign random latitude and longitude,  utilizing a simple Python library and the Open Weather Map API. 

The challenge began by creating a series of scatter plots (saved in the output_data folder) to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

(The scatter plots and gmap with hotel locations are saved in the output folder.)
(Brief Analysis of the scatter plots are also under each plots)

The scatter plot of temperature versus latitude shows that the more favourable temperature range 70F-90F are generally 
within the latitude range of -10 to +30. This shows that more suitable range of temperature for human activities are 
around the equator lines depending on personal preferences.

Cloudiness seems to be fairly spread out throughout the entire world. 

wind speed seems to be fairly low in the northen hemisphere compared to southern.

higher the latitude, lower the max tempearture in the northern hemisphere. 

The second part of the challenge is to run linear regression on each relationship. In this, separate the plots for Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) are created. 

In the southern hemisphere the temperature seems to be fairly correlated with the increase in latitude as going towards the equator, the temperature gets higher.

The data shows there is a week correlation between latitude and humidity in the northern hemisphere. similarly the lattitude seems to be weakly correlated between the wind speed and the cloudiness in both the hemispheres. The data doesn't really fit a liner regression model. 

