# Bike_Sharing_Demand
### Simple and multiple linear regression to forecast bike rentals using hourly rental data of the past two years 

This dataset from [Kaggle](https://www.kaggle.com/c/bike-sharing-demand/data) records bike rental data in different conditions including seasons, weather, temperature, windspeed and humidity. This particular bike sharing program involves obtaining membership, rental and returns through a network of kiosk locations which can aid in understanding the mobility of the a city.

The goal of this project is to _forecast bike rental demand at the Capital bikshare program in Washington DC, using hourly bike rentals over the past two years._

### Variables
This dataset consists of 12 data fields; we will use the first 11 variables in our model to predict the 12, number of total rentals: 
1. Datetime - hourly date + timestamp
2. Season - 1 = spring, 2 = summer, 3 = fall, 4 = winter
3. Holiday - whether the day is considered a holiday
4. Workingday - whether the day is neither a weekend nor holiday
5. Weather - 1: Clear, Few clouds, Partly cloudy, Partly cloudy , 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist , 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds , 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
6. Temp - temperature in Celsius
7. Atemp - “feels like” temperature in Celsius
8. Humidity - relative humidity
9. Windspeed - wind speed 10. casual - number of non-registered user rentals initiated
11. Registered - number of registered user rentals initiated
12. Count - number of total rentals

### Methodology 
Light pre-processing of the data and then constructed simple linear regression and multiple linear regression machine learning models. Interpretation of results, variables and models is also included. 
