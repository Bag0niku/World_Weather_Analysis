# World_Weather_Analysis

## Use today's current weather to plan for a spontaneous vacation.

### Resources:
 - Data: Open Weather Map's Api and saved as CSV files.
 - Software: 
     - Python 3.7.13, Pandas 1.3.5, Numpy 1.21.5, matplotlib 3.5.1, CitiPy 0.0.5
     - Jupyter Notebook (notebook server 6.4.8, Ipython 7.31.1)
     - API keys (Required): Google Maps 
     - API keys (optional): Open Weather Map
       - Current Weather Data retrival step can be skipped if a previous Weather_Database.csv has been saved and you do not mind using older data (from July 23, 2022).

## Summary 
WeatherPy.ipynb and VacationPy.ipynb were my initial exploring of the data available with Open Weather Map's api and Google Maps API.  
 - WeatherPy.ipynb generated 1500 datapoints retrived current weather for about 580 cities around the world.
    - made several scatterplot graphs of the data gathered, comparing city Latitude with the different metrics
 - In VacationPy.ipynb I graphed the information using google maps' Heatmaps. 
 - Weather_Database uses 10,000 data points to get weather data for 2,000 to 3,000 cities accros the world. 

### Vacation_Search Filters that data with user input to find the most likely places to have a vacation.
![](/Vacation_Search/WeatherPy_Vacation_map1.png)
![](/Vacation_Search/WeatherPy_Vacation_map2.png)

### Vacation_Itinerary is a mock vacation result
![](/Vacation_Itinerary/Vacation_Itinerary_map_markers.png)
![](/Vacation_Itinerary/Vacation_Itinerary_map.png)



