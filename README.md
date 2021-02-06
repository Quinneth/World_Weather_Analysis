# World_Weather_Analysis

# Purpose
Using gmaps API and OpenWeather API, scrape data and create a customer travel destination map and itineray map with markers and location markers fthat includes hotels within a certain radius of the cities where customers travel
## Overview
- Use input statements so customers can filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels.
- Four cities where chosen to create a driving itinerary example with an additiional marker layer map.

### Deliverables
- Deliverable 1: Retrieve Weather Data
  - A set of 2,000 random latitudes and longitudes were used to retrieve the nearest city and perform an API call with the OpenWeatherMap. In addition to the city weather data gathered, the API was scraped to retrieve the current weather description for each city. A new DataFrame containing the updated weather data was created.
- Deliverable 2: Create a Customer Travel Destinations Map
  - Customer weather preferences were used to identify potential travel destinations and nearby hotels. Those destinations were displayed on a map with pop-up markers.
- Deliverable 3: Create a Travel Itinerary Map
  - Google Directions API was scraped to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. 
  - A layered map with a pop-up markers for each city on the itinerary was created.
