# World_Weather_Analysis
Analyzing weather data using API's and creating an itenerary for travelers using API's.

## Overview
In this project I used API's to retreive weather data for cities around the world and create a vacation Itenrary based on user preferences.

Data was retrieved using the [openweathermap.org] API and saved into a CSV file.

After data was retrieved, it was stored in a DataFrame and filtered based on user input for minimum and maximum temperature. From there used an API to find the nearest hotel for each city and display the data in a gmap with markers. I used the [gmap api](https://jupyter-gmaps.readthedocs.io/en/latest/api.html) to create the maps in my jupyter notebook.

![gmap with markers](/Vacation_Search/WeatherPy_vacation_map.png)

Then a travel itinerary was created with 4 selected locations on the map. A travel layer was created and displayed over the map.

![gmap with trip](/Vacation_Itinerary/WeatherPy_travel_map.PNG)

Finally, I displayed just the 4 destinations with their map markers.
![gmap with trip markers](/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)