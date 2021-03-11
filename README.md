# World_Weather_Analysis

## Overview
The purpose of this assignment was to extract live information from Google API and OpenWeatherMap to effectively create a custom travel map that included weather data. The overall project can be broken into three deliverables

1.) Weather Data Retrieval

2.) Customer Travel Destinations Map Creation

3.) Travel Itinerary Map Creation

### Deliverable 1 - Weather Data Retrieval

In the first deliverable, we first generated a random set of 2000 coordinates, got the nearest city using the citipy module, performed an API call with the OpenWeatherMap to retrieve various data (Humidity, Temperature, Cloudiness etc..), added the data to a dataframe  then exported the data as a CSV file.

The code can be found in the Weather_Database.ipnyb file. Below is the Dataframe product from the weather API call:

![](https://github.com/niklasax/World_Weather_Analysis/blob/main/Screen%20Shot%202021-03-11%20at%2012.44.52%20PM.png)

### Deliverable 2 - Customer Travel Destinations Map Creation



In the second deliverable, we imported the weather data csv (created in deliverable 1), wrote an input statement that prompted the user to enter their minimum and maximum temperature criteria for their vacation, created filtered and cleaned a dataframe based on user inputs, used gmaps to identify the nearest hotels that fit the parameters then plot those hotels on Google Maps.

The code can be found in the Vacation_Search.ipnyb file. Below is the Google Maps product showing all the potential hotels:

![](https://github.com/niklasax/World_Weather_Analysis/blob/main/Screen%20Shot%202021-03-11%20at%202.35.00%20PM.png)


### Deliverable 3 - Travel Itinerary Map Creation

In the last portion of the assignment, we used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.

The code can be found in the Vacation_Itinerary.ipnyb file. Below is the Google Maps product showing the four chosen hotels and the routes between:

![](https://github.com/niklasax/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
