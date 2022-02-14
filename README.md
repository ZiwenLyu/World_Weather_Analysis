# World_Weather_Analysis

# Overview of this project
This project is to help PlanMyTrip company design a product which can recommend ideal cities and hotels based on clients' weather preference. To complete this task, I did two researches. In the first research, I firstly randomly generated a set of 1,500 random latitudes and longitudes, then retrieved the nearest city, and performed an API call with the OpenWeatherMap. I got around 500 cities and their weather data. Secondly, I did an exploratory analysis with scatter visualization to display how cities' locations related to their weather conditions: such as latitude vs. wind speed, latitidue vs. cloudiness, latitidue vs. humidity, and determine the correlations for those variables. Third, I created a heatmap to show the weather and possible travel spots on a gmap. 

In the second research, I generated a set of 2,000 random latitudes and longtitudes and retrieved around 700 nearest cities. Then, I designed two programs for user to planning trips: one is to identify potential travel destinations and nearby hotels based on user inputs for their preferred weather temperatures, anotehr one is to generate travel itnerary that shows the route between four cities chosen from the customer’s possible travel destinations. 

# The Results

## Identify Potential Travel Spots and hotels
The figure below shows the recommended travel cities and hotels for preferred temperature 75 °F -- 90 °F.
![Identify potential travel destinations and hotels](https://github.com/ZiwenLyu/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Generate a Travel Itinerary with hotels
The figure below shows recommended travel itinerary for four potential travel cities and hotels based on users' preferred country and weather temperatures.
![Generate a Travel Itinerary with hotels](https://github.com/ZiwenLyu/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
