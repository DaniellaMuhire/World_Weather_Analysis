# World_Weather_Analysis
## Project Overview
Task: Collect and analyze weather data across cities worldwide.
Purpose: a travel technology company will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
## Results
1. Generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. Retrieved the current weather description for each city then, created a new DataFrame containing the updated weather data.

[WeatherPy_Database](Weather_Database/WeatherPy_Database.csv)

<img width="1440" alt="Weather_Database" src="https://user-images.githubusercontent.com/77806210/198415599-3f5241a8-dd37-4086-8d6e-4f7fc189ef43.png">

2. Used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

<img width="1440" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/77806210/198415985-8eedcf45-848f-4ecb-b516-f560aa441cbd.png">

3. Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.

<img width="1440" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/77806210/198416229-a4ab255f-9069-4c3a-bb1c-4bcbdd5a557c.png">
