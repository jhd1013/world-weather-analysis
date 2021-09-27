# world-weather-analysis
This project does the following:
- Generates are random set of earth coordinates
- Uses citipy to locate the nearest city to those coordinates; drops the coordinates if no result
- Pulls current weather data via the openweathermap.org API for each remaining city
- Finds lodging in each city using the Google Places API and plots it on a map using gmaps
- Using weather data and user input for temperature, filters the set down to match that input
- Using Google Directions API, plot driving directions on a map using gmaps
