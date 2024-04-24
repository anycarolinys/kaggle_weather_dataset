# **Kaggle Latin America Weather Dataset**

<!-- ![alt text](./LA_map.png) -->
<img src="https://media.istockphoto.com/id/1048148458/pt/vetorial/map-of-latin-america.jpg?s=612x612&w=0&k=20&c=RrFymUIwQdELHW5oDGeEgdJzr5pUAxV7hwmlXu7QzcQ=" alt="Latin America Map" width="300"/>  

Fonte: iStock (2018)

# Open-Meteo API Project

This project is an application that makes requests to the Open-Meteo API to obtain climate and air quality data.

## Climate Parameters

The application retrieves the following daily climate parameters for the specified latitude and longitude between January 1, 2020, and April 20, 2024:

- Maximum 2m temperature
- Minimum 2m temperature
- Mean 2m temperature
- Maximum apparent temperature
- Minimum apparent temperature
- Mean apparent temperature
- Total precipitation
- Maximum 10m wind speed
- FAO evapotranspiration (et0_fao_evapotranspiration)

## Air Quality Parameters

The application also retrieves the following daily air quality parameters for the specified latitude and longitude between July 29, 2022, and April 20, 2024:

- PM10
- PM2.5
- Carbon monoxide
- Nitrogen dioxide
- Sulphur dioxide
- Ozone

## Usage

To use this application, you need to replace `latitude_list` and `longitude_list` in the `climate_params` and `air_quality_params` dictionaries with your desired latitude and longitude values.

## Dependencies

This project requires Python 3.6 or later and uses the `requests` library to make HTTP requests to the Open-Meteo API.
