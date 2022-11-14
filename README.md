# What's the Weather Like?

## 📝 Project Description

![equator](Images/equatorsign.png)

Whether financial, political, or social&mdash;data's true power rests in its ability to answer questions definitively. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter ..."_

But, if pressed, how would you **prove** it?

## 🌤️ Part 1: WeatherPy

In this section, a Python script was used to visualize the weather of 500+ cities of varying distance from the equator. 
Used citypy library and OpenWeatherMap API to create a representative model of weather across cities.

A series of scatter plots was created to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

### 🌴 Part 2: VacationPy

* Creating a heat map that displays the humidity for every city from Part 1, as in the following image:

  ![heatmap](Images/heatmap.png)

* Using Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.

* Plotting the hotels on top of the humidity heatmap, with each pin containing the **Hotel Name**, **City**, and **Country**, as in the following image:

  ![hotel map](Images/hotel_map.png)

## 📚 References


© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
