# World Weather Analysis

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

# Deliverable #1 - Retrieve Additional Weather Data

  - We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data we previously gathered, we also retrieved the current weather description for each city. Finally, we created a new DataFrame containing the updated weather data.
  
# Deliverable #2 - Create a Customer Travel Destinations Map

  - We used input statements to retrieve customer weather preferences and then used those preferences to identify potential travel destinations and nearby hotels. Then we displayed those destinations on a marker layer map with pop-up markers.
  
# Deliverable #3 - Create a Travel Itinerary Map

  - We used the Google Directions API to create a travel itinerary that shows the route between the four cities chosen from the customer’s possible travel destinations. Then we created a marker layer map with a pop-up marker for each city on the itinerary.
  
# APIs Used
- OpenWeather API
- Google Maps Places API
- Google Maps Directions API
