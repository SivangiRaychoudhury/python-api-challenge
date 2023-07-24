# python-api-challenge
 
Part 1: WeatherPy
Using the python script, citipy library and the OpenWeatherMap API, the given issues were solved to create a representative model of weather across the cities. 

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, I have used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Then, I have  created a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
DataFrames for Northern hemisphere and Southern hemisphere are created. Then a series of scatter plots are created where the linear regression line, the model's formula, and the r values are included.
Following plots are created:
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude
After each pair of plots, the linear regression is modeling is explained and any relationships that are noticed and any other findings are described.

Part 2: VacationPy
Using Jupyter Notebooks, the geoViews Python library and the Goeapify API, the following calculations are done and findings are generated in form of maps. 

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:
1.Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity    in each city.
2.Narrow down the city_data_df DataFrame to find your ideal weather condition. 
  For example:
  A max temperature lower than 27 degrees but higher than 21
  Wind speed less than 4.5 m/s
  Zero cloudiness
3.Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4.For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5.Add the hotel name and the country as additional information in the hover message for each city on the map.
