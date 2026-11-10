# Weather Information App 🌤️

## Overview
This project is a Python-based weather application that retrieves real-time weather information for different cities using the OpenWeatherMap API. It demonstrates how to work with external APIs, send HTTP requests, process JSON responses, and extract weather-related data using Python.

## Features
- Retrieve real-time weather information by city name.
- Send HTTP GET requests using the `Requests` library.
- Process API responses in JSON format.
- Extract city names and geographical coordinates.
- Retrieve temperature information in Celsius using PyOWM.

## Technologies & Libraries
- Python
- Requests
- JSON
- OpenWeatherMap API
- PyOWM

## Project Structure
The project demonstrates two approaches to accessing weather data:

1. **Requests Method:** Connects directly to the OpenWeatherMap API and retrieves weather information through HTTP requests.
2. **PyOWM Method:** Uses the PyOWM library to access weather data and extract the current temperature.

## Example Output
```text
Enter city name: Tehran

City: Tehran
Longitude: 51.4167
Temperature: 18.5°C
```

*Note: The output values depend on the selected city and current weather conditions.*

## Learning Objectives
- Understanding REST APIs.
- Working with HTTP GET requests.
- Handling JSON data in Python.
- Using external Python libraries.
- Retrieving and processing real-time weather data.

## API
Weather data is provided by [OpenWeatherMap](https://openweathermap.org/api).
