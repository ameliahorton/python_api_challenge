# python_api_challenge
In this assignment, I used OpenWeatherMaps API to check several aspects of the weather conditions in around 500 cities, as well as their latitude and longitude. Using this information I was able to create several visualizations to show trends in how latitude affects temperature, humidity, cloudiness, and wind speed. I observed the following trends:
    1) Higher temperatures tend to be found closer to the equator, or where the absolute value of the latitude is lowest. Lower temperatures are usually found at opposite extremes of latitude- both the lowest and highest latitude values in our dataset.
    2) Humidity, cloudiness, and wind speed all appear to be less affected by latitude than temperature.
    3) Weather trends separated by hemispheres are often mirrors of each other. For example, while the temperature decreases with latitude in the northern hemisphere, the opposite is true in the southern hemisphere.
 
In the second part of the assignment, VacationPy.ipynb, I set some parameters to describe my ideal weather conditions for going on vacation. I created a dataframe containing only cities from the original dataframe that satisfied these conditions, and then I used the Google Places API to find the nearest hotel for the coordinates (Lat, Lng) of each city. Finally, I plotted all of these on a map, along with a humidity heatmap layer. 
 
This is Assignment 6 for the Northwestern Data Science Bootcamp. I worked with TA Erin Wills on this assignment.
