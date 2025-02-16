# Weather App - Project Description

## Overview

The Weather App is a simple web-based application that allows users to search for a city and view real-time weather data. It fetches data from the OpenWeatherMap API and displays weather conditions such as temperature, humidity, wind speed, and pressure. The app is built using HTML, CSS, and JavaScript.

## Features

- Search for a city to get live weather updates.
- Displays current temperature, humidity, wind speed, and pressure.
- Shows minimum and maximum temperature for the day.
- Displays weather forecast condition (e.g., sunny, rainy, cloudy).
- Shows a weather icon representing the current condition.
- Displays the current date and time based on the searched city's location.

## Technologies Used

- HTML: Structure of the webpage.
- CSS: Styling and layout.
- JavaScript: Fetching and processing weather data from the API.

---

## Code Breakdown

### 1. HTML (Structure)

- The input field allows users to enter a city name.
- A main weather display section shows temperature, weather condition, and city details.
- Extra weather details (feels like temperature, humidity, wind speed, and pressure) are displayed in separate cards.

### 2. CSS (Styling)

- Uses Google Fonts for better typography.
- Dark theme design with a modern UI.
- Grid layout for better arrangement of weather information.
- Responsive design to work on all screen sizes.

### 3. JavaScript (Functionality)

- Event Listener: Listens for user input and fetches weather data.
- Fetch API: Retrieves weather data from OpenWeatherMap.
- Dynamic Content Update: Updates the webpage with the fetched data.
- Date & Time Formatting: Converts the timestamp into a readable format.
- Error Handling: Catches API errors and logs them to the console.

---

## How It Works

1. The user enters a city name in the search bar.
2. The app fetches data from OpenWeatherMap API.
3. The weather details update dynamically on the page.
4. The user can view temperature, forecast, wind speed, humidity, and pressure.

---

## Possible Improvements

- Add unit conversion (Celsius/Fahrenheit).
- Improve error handling for invalid city names.
- Display hourly & weekly forecasts.
- Add a location-based weather feature.
