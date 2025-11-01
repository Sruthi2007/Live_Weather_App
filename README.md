🌦️ Weather Dashboard

A responsive weather forecasting web app built using HTML, CSS, and JavaScript that provides real-time weather, air quality, and forecast data for any city. 
The app uses the OpenWeather API to display key metrics like temperature, humidity, pressure, visibility, AQI, sunrise/sunset times, and a 5-day forecast — all presented in a clean, modern interface.

🚀 Features

✅ Search Any City — Get real-time weather details by entering a city name.
✅ Current Weather Info — Displays temperature, sky condition, humidity, pressure, and feels-like temperature.
✅ Air Quality Index (AQI) — Shows CO, NO₂, O₃, and SO₂ concentration levels using the Air Pollution API.
✅ Sunrise & Sunset Times — Automatically converts UTC timestamps to local time format.
✅ Hourly Forecast — Shows the next few hours’ predicted temperatures and conditions.
✅ 5-Day Forecast — Displays upcoming weather for the next five days.
✅ Responsive Design — Works seamlessly across mobile, tablet, and desktop.

🛠️ Technologies Used
Category	  Technology
Frontend	  HTML5, CSS3 (Flexbox, Media Queries)
Scripting	  JavaScript (ES6+), jQuery
API	        OpenWeatherMap APIs (Weather, Forecast, Air Pollution)
Design  	  Custom responsive layout with glassmorphism styling

⚙️ API Setup

This app uses OpenWeatherMap APIs.
To run it on your own:

Go to https://openweathermap.org/api

Create a free account.

Copy your API key.

Replace it in the script section of your code:

const apiKey = "YOUR_API_KEY_HERE";

🧠 How It Works

When the user enters a city name and clicks the search icon, the app:

Fetches current weather data from the Weather API.

Retrieves AQI data based on latitude and longitude.

Calls the Forecast API to display 5-day and hourly temperatures.

Dynamically updates all values on the dashboard in real time.

🌍 API References

Current Weather Data: https://api.openweathermap.org/data/2.5/weather

5-Day / 3-Hour Forecast: https://api.openweathermap.org/data/2.5/forecast

Air Pollution Data: https://api.openweathermap.org/data/2.5/air_pollution
