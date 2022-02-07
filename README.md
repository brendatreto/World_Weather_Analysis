# World Weather Analysis

For this assignment we were given the task to improve the PlanMyTrip App. 

## Resources
-Python 3.7.6
-Jupyter Notebook
-Google API
-World Weather API


## Retrieving the data
The first step consisted in creating a set of 2000 random latitudes and longitudes to perform an API call to OpenWheaterMap. With that information we created a new DataFrame to keep working on.

## Creating a customer travel destinations map
The next step in the process was to ask users about their preferences in temperature and iterate through the exising data to get the wanted results. After that we perform a different API Call with Google Services to retrieve information of hotels nearby and show them in a map. 

Fig.1 Travel destinations map
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/22451540/152891588-999486e7-8ff3-4103-90ec-18e23d5650c5.PNG)

## Create a travel itinerary Map
We finished the process by using Google Directions API to create a travel itinerary and show a route between four of the filtered cities. This way, our user could plan their trip accordingly.

Fig 2. Vacation itinerary
![WeatherPy_travel_map](https://user-images.githubusercontent.com/22451540/152891729-70c01b7d-c38f-400f-b7fc-44bbafbc099f.PNG)
