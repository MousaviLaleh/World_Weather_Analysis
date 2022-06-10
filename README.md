# World_Weather_Analysis

## Project Overview
Work with PlanMyTrip travel technology company, to improve thier travel services andthe PlanMyTrip app, by adding following features in the search page; using Python, Pandas, Jupyter notebook, citipy and matplotlib module, openweathermap and google APIs.
  
  - Get the cities for more than 500 random latitude and longitude.
  - Perform requests with APIs.
  - Retrieve the json weather data from these cities.
  - help customers to predict the best time of year to plan thier vacation.

## Purpose
Take following steps in this project:

  - Retrieve Weather Data.
  - Add weather description to the weather data.
  - Add input option to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels.
  - Create a Customer Travel Destinations Map.
  - Create a Travel Itinerary Map, by using the Google Maps Directions API, to create a travel route between the four cities.

### Resources
  :card_file_box: &#160; [Python 3.6.1](https://www.python.org/downloads/windows/) <br/>
  :card_file_box: &#160; [OpenWeather API](https://openweathermap.org/current) <br/>
  :card_file_box: &#160; [Google Maps and Places API](https://developers.google.com/maps/documentation/places/web-service/search)<br/>
  :card_file_box: &#160; [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/overview) <br/>
  :card_file_box: &#160; [Jupyter Gmaps module](https://jupyter-gmaps.readthedocs.io/en/latest/) <br/>
  :card_file_box: &#160; [citipy module](/fies/615.pdf) <br/>
  :card_file_box: &#160; [matplotlib.pyplot module](https://pandas.pydata.org/docs/user_guide/visualization.html?highlight=matplotlib#plotting-directly-with-matplotlib)
<br/>

## Analysis
### Retrieve Weather Data
- The app uses the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).
- The Python's [citipy](/fies/615.pdf) module is then called to identify the nearest city for each coordinate combination.
- The weather data is retrieved for all identified cities through a request to the [OpenWeather API](https://openweathermap.org/current).

![01.png](/files/01.png)



## Results


## 
