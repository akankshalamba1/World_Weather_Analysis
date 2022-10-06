# World_Weather_Analysis
Weather Analysis of PlanMyTrip

## Fundamental Project Plan
An overview of your project plan is given below:
- **Collect and examine weather information from various cities across the globe.**

- **Goal**: PlanMyTrip will use the information to suggest the best hotels depending on the weather preferences of its customers.

- **Approach**: Build a Pandas DataFrame with at least 500 distinctive cities from around the globe and their current weather information. Data collection, analysis, and visualization are all parts of this process.

There will be three primary phases of data analysis.

### 1. Gather the Data
- Generate more than 1,500 random latitudes and longitudes using the NumPy package.
- List the closest cities to the latitudes and longitudes using the citipy module.
- To obtain the most recent weather information from each, use the OpenWeatherMap API.
- Parse the API request's JSON data.
- Gather the data from the JSON file and add it to a DataFrame as follows:
   - City, nation, and date
   - Longitude and latitude
   - Maximum temperature
   - Humidity
   - Cloudiness
   - Wind speed

![database](https://user-images.githubusercontent.com/111251560/194207121-72e66495-e4b9-4682-a67a-7f509e0d9e1c.png)

### 2. Visualized Exploratory Analysis
- Produce scatter plots using the weather information for the following comparisons:
- Temperature versus latitude
- Humidity versus latitude
- Latitude in relation to cloudiness
- Latitude in relation to wind speed

**Ascertain the relationships between the subsequent weather data:**
- Temperature and latitude
- Humidity and latitude
- Cloudiness and latitude
- Latitude and wind velocity

![WeatherPy_vacation](https://user-images.githubusercontent.com/111251560/194207199-d825948a-9326-4807-b656-83f9420c4825.png)

### 3. Make Travel Data Visual
Create a marker layer map with pop-up markers that can show details about particular cities depending on the travel interests of a consumer. Follow these instructions:
-  Filter the Pandas DataFrame based on the 4 selected hotels from the temprature range selected by the end user.
- Use the Search Nearby function of Google Maps and Places API to find hotel information based on the locations of the cities.
- Save the first hotel's name in the DataFrame.
- Include pop-up markers on the marker layer map that show details about the city, country, hotel name, current temprature and latitude and longitude.

### Plotting the marker layer map to show the itenerary:
As shown in the picture below:

![WeatherPy_travel_map](https://user-images.githubusercontent.com/111251560/194207247-1dd02d0b-8361-46a1-a0ff-6abd2b340c1e.png)

![WeatherPY_travel_map_markers](https://user-images.githubusercontent.com/111251560/194207278-cff044f9-3aa1-4532-9343-37cf5309c9ae.png)

