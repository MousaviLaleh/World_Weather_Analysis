# World_Weather_Analysis

## Project Overview
Work with PlanMyTrip travel technology company, to improve thier travel PlanMyTrip app services, by adding features in the search page; using *Python, Pandas, Jupyter notebook, citipy and matplotlib module, openweather map and google APIs*. Based on the new features , users can filter their preferred travel criteria in order to find their ideal hotel anywhere, and predict the best time of year to plan their vacation.


## Purpose
The purpose of this project consists of three technical analyses.
  - Retrieve Weather Data.
  - Create a Customer Travel Destinations Map.
  - Create a Travel Itinerary Map.


### Resources
  :card_file_box: &#160; [Python 3.6.1](https://www.python.org/downloads/windows/) <br/>
  :card_file_box: &#160; [OpenWeather API](https://openweathermap.org/current) <br/>
  :card_file_box: &#160; [Google Maps and Places API](https://developers.google.com/maps/documentation/places/web-service/search)<br/>
  :card_file_box: &#160; [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/overview) <br/>
  :card_file_box: &#160; [Jupyter Gmaps module](https://jupyter-gmaps.readthedocs.io/en/latest/) <br/>
  :card_file_box: &#160; [citipy module](/files/615.pdf) <br/>
  :card_file_box: &#160; [matplotlib.pyplot module](https://pandas.pydata.org/docs/user_guide/visualization.html?highlight=matplotlib#plotting-directly-with-matplotlib)
<br/>

## Analysis
### Retrieve Weather Data
take the steps:
- The app uses the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).
- The Python's [citipy](/files/615.pdf) module is then called to identify the nearest city for each coordinate combination.
- The current weather data is retrieved for all identified cities through a request to the [OpenWeather API](https://openweathermap.org/current).

![01.png](/files/01.png)
<br/>
<br/>

### Create a customer travel destinations map
take the steps:
- use input statements to retrieve customer weather preferences.<br/>
  ![inBox.png](/Vacation_Search/inBox.png)
- use those preferences to identify potential travel destinations and nearby hotels.
- show those destinations on a map with pop-up markers.

![WeatherPy_vacation_map.png](/Vacation_Search/WeatherPy_vacation_map.png)
<br/>
<br/>




## Results


## notes
 - Add weather description for each city to the weather data.
  - Add input option to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels.
  - Create a Travel Itinerary Map, by using the Google Maps Directions API, to create a travel route between the four cities.
  -   
  - Get the cities for more than 500 random latitude and longitude.
  - Perform requests with APIs.
  - Retrieve the json weather data from these cities.
  - help customers to predict the best time of year to plan thier vacation.



