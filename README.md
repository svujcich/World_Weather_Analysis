# World_Weather_Analysis

This project focuses on using weather trends to inform travel decisions. This code generates a dictionary of random latitude and longitude coordinates, then finds the city nearest to each location using citipy. The code then calls on a [Weather API](https://openweathermap.org/api) to access weather information such as temperature, humidity, current weather descriptions for each location, in order to create a data frame of cities.

Next, the list of cities if refined by the temperature preferences of the vacation goer. The [Google Maps Platform API](https://mapsplatform.google.com/) is used to locate nearby hotels for each candidate city. All potential cities are then displayed on a world map using a marker, which if clicked on, displays pop up information about each potential vacation destination
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106559768/181423489-04c554d6-3c0f-42fb-abd8-bbfd28b00521.png)

Finally, 4 destinations within driving distance of each other are selected for the last step in the vacation planning process.  Using the Google Maps Platform API, a directions layer is added to a map featuring only the selected vacation locations. Each waypoint is enabled with info boxes, which if clicked, reveal the specific hotel, location, and weather information for each stop. 
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106559768/181423672-89e03e19-5f3f-42f0-b08f-24757462e5ab.png)
