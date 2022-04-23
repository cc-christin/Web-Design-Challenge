# Web-Design-Challenge
Used HTML and CSS to create a dashboard showing off the analysis from weather data. Individual pages were created for each plot and a means by which we can navigate between them was devised. The website consist of 7 pages total and was deployed to github pages. 

[GitHub Pages Link for Web-Design-Challenge](https://cc-christin.github.io/Web-Design-Challenge/)

Website Pages
* /landing.html
* /data.html
* /comparisons.html
* /cloudiness.html
* /humidity.html
* /max_temp.html
* /windspeed.html


# Overview:
This project analyzes changes in weather in relation to latitide from the euqator. Original data was pulled from the OpenWeatherMap API to generate a dataset of over 500 cities and used to generate the various plots. Matplotlib was used to generate the plots for latitide vs. (cloudiness, humidity, temperature, and windspeed) respectively.

# Visualizations

After gathering and analyzing api data on weather conditions: temperture, humidity, cloud cover, wind speed, and geolocation (latitudinal distance from the equator) for 565 cities in both the northern (384) and southern (181) hemisphere for the month of Febuary 2022, there seems to be a strongly negative correlation between temperature (in degrees Fahrenheit) and geolocation from the equator for cities in the northern hemisphere and a slightly positive correlation for the same metrics for cities located in the southern hemisphere. The farther away a city is located from the equator (0 degrees latitude) the colder the climate, mainly for the ranges beyond the range of -20 to 20 (degrees latitude). There seems to be little to no statistically relevent correlation between humidity, cloudiness, and wind speed with geolocation in respects to the equator as the data points are spreaded throughout and does not form a logical pattern that when not skewed by server outliers. Wind speed between over 30 mph can be found for a specific cities in the northern hemisphere located between 60 and 70 (degrees latitude) such as Sørland (67.6670, 32.26). There are also outliers like Isangel (40.18, -19.5500) and Vao (-22.6667, 30.29) for the southern hemisphere with also with over 30 mph wind speeds. There is no observable correlation for cloudiness (cloud cover) and geolocation for all cities (both north and south of the equator). The data points appear to be randomly scattered all through out the linear regression plot with no obvious association that can be analyzed.


![cloudiness.png](https://github.com/cc-christin/Web-Design-Challenge/blob/main/assets/cloudiness.png) 
![humidity.png](https://github.com/cc-christin/Web-Design-Challenge/blob/main/assets/humidity.png) 

![max_temp.png](https://github.com/cc-christin/Web-Design-Challenge/blob/main/assets/max_temp.png) 
![windspeed.png](https://github.com/cc-christin/Web-Design-Challenge/blob/main/assets/windspeed.png) 
