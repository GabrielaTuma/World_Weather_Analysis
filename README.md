# World_Weather_Analysis
Module 6 - World_Weather_Analysis

## Project Overview

Retrieve Weather Data, create a customer travel destinations map and a travel itinerary map.


Deliverable 1
- [x] 1. Retrieve the information from the API call
- [x] 2. Add the weather data to a new DataFrame
- [x] 3. Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder

[Weather_Database](https://github.com/GabrielaTuma/World_Weather_Analysis/tree/main/Weather_Database) folder:
- [x] The Weather_Database.ipynb file
- [x] The WeatherPy_Database.csv file

Deliverable 2
- [x] 1. Input statements are written to prompt the customer for their minimum and maximum temperature preferences
- [x] 2. A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped
- [x] 3. The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped
- [x] 4. The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv
- [x] 5. A marker layer map with pop-up markers for the cities in the vacation DataFrame
- [x] 6. The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png

[Vacation_Search](https://github.com/GabrielaTuma/World_Weather_Analysis/tree/main/Vacation_Search) folder:
- [x] The Vacation_Search.ipynb file
- [x] The WeatherPy_vacation.csv file
- [x] The WeatherPy_vacation_map.png image


Deliverable 3
- [x] 1. Four DataFrames are created, one for each city on the itinerary
- [x] 2. The latitude and longitude pairs for each of the four cities are retrieved
- [x] 3. A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png
- [x] 4. A DataFrame that contains the four cities on the itinerary is created
- [x] 5. A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png

[Vacation_Itinerary](https://github.com/GabrielaTuma/World_Weather_Analysis/tree/main/Vacation_Itinerary) folder:
- [x] The Vacation_Itinerary.ipynb file
- [x] The WeatherPy_travel_map.png image
- [x] The WeatherPy_travel_map_markers.png image


## Resources 

- Weather API: [OpenWeather](https://openweathermap.org/current)
- Maps API: [Google Cloud Platform](https://developers.google.com/maps)
- Software: Python 3.7.6, Visual Studio Code 1.58.1, Jupyter Notebook 6.3.0
 
 
## Outcomes

In the **first deliverable** an API call was made using OpenWeather and a database was created with the following information: 

<kbd>
  <img src="https://github.com/GabrielaTuma/World_Weather_Analysis/blob/532145aa194df432e4c308f7f005f1f549613b51/Weather_database.png">
</kbd>  &nbsp;




In the **second deliverable** two inputs were created for the Max Temp variable and a new DataFrame was generated using 75°F and 90°F for minimum and maximum temperature respectively.

With the new DataFrame and using Google APIs it was possible to visualize hotels and destinations options on a map:

![Vacation Search](https://github.com/GabrielaTuma/World_Weather_Analysis/blob/07fc6156e9e9efec06cf92464d1d2d875b19c793/Vacation_Search/WeatherPy_vacation_map.png)


For **deliverable 3** four cities in Brazil were chosen to be the travel destinations:
- Itarema
- Acaraú
- Beneditinos
- Touros

the DataFrame below was used to summarize the information from each city and create an itinerary starting and ending in Itarema.

![DataFrame](https://github.com/GabrielaTuma/World_Weather_Analysis/blob/07fc6156e9e9efec06cf92464d1d2d875b19c793/Itinerary_cities_df.png)

The following itinerary was generated using the "Driving" travel mode: 
<img src="https://github.com/GabrielaTuma/World_Weather_Analysis/blob/07fc6156e9e9efec06cf92464d1d2d875b19c793/Vacation_Itinerary/WeatherPy_travel_map.png" width="100%" height="100%">

In order to better plan this vacation, a map showing a hotel option for each city and some weather information was created as well:

![Itinerary with marks](https://github.com/GabrielaTuma/World_Weather_Analysis/blob/07fc6156e9e9efec06cf92464d1d2d875b19c793/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

