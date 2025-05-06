# WEATHER API FROM 2022-2025
## Project overview
To visualize weather data over time, evaluating it's effect on different industries.
To predict weather like temperature_2m , relative humidity_2m and precipitaion of New york city, USA using historical data from 2022-2025 from open weather API.
This API extracts historic data for  hourly temperature_2m, relative humidity_2m and precipitation. 
## Tools
- [openmeteoAPI](https://open-meteo.com/)
- Python
## Procedure
- Setup the Open-Meteo API client with cache and retry on error
- Make sure all required weather variables are listed here
- The order of variables in hourly or daily is important to assign them correctly below
- Process hourly data. The order of variables needs to be the same as requested.
- Convert dataframe to csv, check for null values and have a overview of data
- Run a quick statistical overview of data
- Run correlation
- Plot line plot of temperature_2m, relative humidity_2m, precipitation over time
- Build models for predicting weather using linear regression
- plot line plot comparing actual weather vs predicted weather conditions

## conclusion
### According to correlation test
- Temperature, humidity and precipitation are negatively correlated with time 
- Temperature and humidity are negatively correlated to precipitation
- Temperature is positively correlated to humidity
### prediction
- Predicted temperature and humidity shows a slight drop to the actual temperature and humidity over time
- The predicted precipitation goes below the actual precipitation with no significance difference over time 
  
