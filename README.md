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

### 3. Make Travel Data Visual
Create a marker layer map with pop-up markers that can show details about particular cities depending on the travel interests of a consumer. Follow these instructions:
-  Filter the Pandas DataFrame based on the 4 selected hotels from the temprature range selected by the end user.
- Use the Search Nearby function of Google Maps and Places API to find hotel information based on the locations of the cities.
- Save the first hotel's name in the DataFrame.
- Include pop-up markers on the marker layer map that show details about the city, country, hotel name, current temprature and latitude and longitude.

### Plotting the marker layer map to show the itenerary:
As shown in the picture below:
