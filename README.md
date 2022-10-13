# World_Weather_Analysis

## Overview of the Project
### Background and Purpose
PlanMyTrip is a top travel technology company, specializing in internet-related services in the hotel and lodging industry. Jack, who is the head of analysis for the UI team, has asked for help collecting and presenting data from customers via the search page. Customers input their preferred weather crtieria in order to find their ideal potential travel destinations and nearby hotels anywhere in the world. Customers also have the option to create a travel itinerary for up to four cities and a travel route will be created for them.

### Resources
- Data Source: OpenWeatherMap API, Google Places API, Google Maps Directions API
- Software: Jupyter Notebook, Matplotlib, Python

## Project
### Rerieve Weather Data
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

### Create a Customer Travel Destiantion map (Vacation Search
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

### Create a Custom Intiernary 
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.
