# **Kaggle Latin America Weather Dataset**

<!-- ![alt text](./LA_map.png) -->
<img src="./LA_map.png" alt="Latin America Map" width="300"/>  

Fonte: PNGItem (2024)

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

The application also retrieves the following hourly air quality parameters for the specified latitude and longitude between July 29, 2022, and April 20, 2024:

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