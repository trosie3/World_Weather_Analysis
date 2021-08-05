# World Weather Analysis

## Purpose and Overview
To find and create a possible vacation plan of four cities in one country based on a clients preferred temperature range. The applications made are to show how to get the itinerary if the client had put in a min temperature of 75 and a max temperature of 90 with this city data set. 

## Resources
CitiPy
Gmaps API
Open Weather API

## Results and Summary
Analyzed 2000 random longitude/latitude combos, of those 766 were near cities. Of those 766 cities, 708 had weather data to pull from. After the preferred temperature was added via a ‘client’s input’ the list was narrowed down to 251 cities within those params. Next, I searched the data for cities with hotels which narrowed down the list a bit further to 232 cities with hotels. With that list, I then searched for a country which had four cities listed within all those requirements. In this dataset, Japan met all those requirements so a vacation itinerary with maps was complied. See images below.

All possible locations:

  ![image](https://github.com/trosie3/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map2.png)

Itenray built based on 4 cities in same country and in the right temperature range:
  ![image](https://github.com/trosie3/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
  ![image](https://github.com/trosie3/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

## Limitations 
The data was random, which means there is no way of knowing if the cities I ended up pulling into the dataset were countries that allow for tourism, even if they have hotels. Also, many countries likely have four cities to visit were ruled out because the dataset was completely random and only pulled in less than four locations, thus I ignored them for making a trip based on four cities in the same country within this dataset parameters. Lastly, most people look at more than what the weather will be like when selecting a trip, for example languages spoken, tourist attractions, how you can get to the starting city i.e., flying, boat, train, etc., cost of those hotels and travel costs so the trip I made might be completely unrealistic.
