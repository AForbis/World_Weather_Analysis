# World Weather Analysis 

# Update the PlanMyTrip app with the following: 

## 1) Deliverable #1 - Retrieve Additional Weather Data

  - We generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data we previously gathered, we also retrieved the current weather description for each city. Finally, we created a new DataFrame containing the updated weather data.
  
  - Results
  
  ![](Del1_df.png)
  
  - Files
  [Weather_Database.ipynb](Weather_Database.ipynb)
  
  [WeatherPy_Database.csv](WeatherPy_Database.csv)
  
  
## 2) Deliverable #2 - Create a Customer Travel Destinations Map

  - We used input statements to retrieve customer weather preferences and then used those preferences to identify potential travel destinations and nearby hotels. Then we displayed those destinations on a marker layer map with pop-up markers.
  
## 3) Deliverable #3 - Create a Travel Itinerary Map

  - We used the Google Directions API to create a travel itinerary that shows the route between the four cities chosen from the customer’s possible travel destinations. Then we created a marker layer map with a pop-up marker for each city on the itinerary.
  
## APIs Used
- OpenWeather API
- Google Maps Places API
- Google Maps Directions API
