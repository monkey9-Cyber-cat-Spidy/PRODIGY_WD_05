# Customizable Weather Forecast

A customizable weather forecast application that uses the Open‑Meteo API to fetch weather data based on a user-entered location. The application displays current, hourly, and daily weather forecasts with smooth GSAP animations, and allows you to download the full JSON response.

## Live Demo

[Live Demo]([https://your-live-demo-link.com](https://prodigy-wd-05-eight-rouge.vercel.app/))

## Features

- **Location Information:**  
  Displays latitude, longitude, timezone, and elevation (if available).

- **Current Weather:**  
  Shows temperature, wind speed, weather code, and wind direction.

- **Hourly Forecast:**  
  Displays the first 12 entries with time, temperature, wind speed, and wind direction.

- **Daily Forecast:**  
  Shows the forecast date, maximum temperature, minimum temperature, and weather code.

- **JSON Download:**  
  Download the complete JSON response from the Open‑Meteo API.

- **GSAP Animations:**  
  Smooth animations for header, form, weather data container, and download button for an enhanced user experience.

## How It Works

1. **Geocoding:**  
   The application uses the Nominatim API to convert the user-entered location (city, state, or country) into geographic coordinates (latitude and longitude).

2. **Fetching Weather Data:**  
   With the obtained coordinates, the app calls the Open‑Meteo API to retrieve the current weather along with hourly and daily forecasts, including temperature data.

3. **Rendering Data:**  
   The app dynamically builds HTML tables to display:
   - **Location Information**
   - **Current Weather**
   - **Hourly Forecast**
   - **Daily Forecast**

4. **Animations:**  
   GSAP is used to animate page elements (header, form, data container, and download button) to create a smooth, interactive experience.

5. **JSON Download:**  
   The full JSON response is stored and linked to a download button, enabling users to download the complete weather data.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/customizable-weather-forecast.git
