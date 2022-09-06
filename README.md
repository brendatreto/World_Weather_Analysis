# World Weather Analysis

For this assignment we were given the task to improve the PlanMyTrip App. On top of the already working functions we were asked to comply with the following features:

`1` Add the weather description on specific locations

`2` Use testers' input to filter data based on weather preferences and identify potential travel destinations

`3` Create a travel route based on the testers' preferences using Google Maps Directions API

## Resources
- Python 3.7.6
- Jupyter Notebook
- Google API
- World Weather API


## Retrieving the data
The first step consisted in creating a set of 2000 random latitudes and longitudes to perform an API call to OpenWheaterMap. With that information we created a new DataFrame to keep working on.

## Creating a customer travel destinations map
The next step in the process was to ask users about their preferences in temperature and iterate through the existing data to get the wanted results. After that we perform a different API Call with Google Services to request information of hotels nearby and show them in a map. 

Fig.1 Input request

![users_input](https://user-images.githubusercontent.com/22451540/188752500-278155d8-3d2a-45f6-b85f-8a932bbc5b14.PNG)

With this information, we filtered the data set to extract only information that matched the wanted characteristics and added a column to our working dataframe with the hotel info and adding that to our map.

Fig.2 Travel destinations map

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/22451540/152891588-999486e7-8ff3-4103-90ec-18e23d5650c5.PNG)

## Create a travel itinerary Map
We finished the process by using Google Directions API to create a travel itinerary and show a route between four of the filtered cities. This way, our user could plan their trip accordingly.

Fig 3. Vacation itinerary

![WeatherPy_travel_map](https://user-images.githubusercontent.com/22451540/152891729-70c01b7d-c38f-400f-b7fc-44bbafbc099f.PNG)
