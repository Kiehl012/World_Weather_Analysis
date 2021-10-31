# Overview

This project utilized OpenWeather and Google Maps APIs in conjuction with gmaps to create heatmaps as well as POI (point of interest) maps. The maps were built via the following process:
- 2,000 random pairs of latitude and longitude coordinates were generated
- Used citipy to find the nearest city to each of those coordinate pairs.
- Used Openweather API to find current weather conditions in each of those cities.
- Used gmaps to create heatmaps of those cities
- Used google places API to find the nearest hotels to each city
- Used weather parameters to show only hotels/cities that met temperature criteria provided by a user.
- Used google directions API to create trip maps between target cities.
