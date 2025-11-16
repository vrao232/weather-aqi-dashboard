🌤️ Power BI Weather & Air Quality (EAQI) Dashboard

A modern, mobile-app–style Weather + Air Quality Dashboard built using Power BI, WeatherAPI, and EAQI (European Air Quality Index) pollutant standards.
This dashboard visualizes real-time weather, 7-day forecasts, and pollutant data such as PM2.5, PM10, NO₂, SO₂, O₃, and CO, using dynamic colors, icons, and DAX intelligence.

📌 Features
🌦️ Weather Insights

Real-time temperature, humidity, wind speed

Weather condition icons (auto-fetched from API)

Feels-like temperature

Sunrise & Sunset visualization

Chance of rain (with visual breakdown)

7-day forecast (Temp, Rain, UV, Icons)

🏭 Air Quality Insights (EAQI Standard)

Pollutants:

PM2.5

PM10

NO₂

SO₂

O₃

CO

EAQI-based levels

Color-coded health indicators

Dynamic DAX-driven pollutant categorization

🛠️ Technical Highlights

Automated WeatherAPI integration (Power Query M script)

7-day forecast extracted for multiple Indian states

Clean and optimized data modeling

EAQI-compliant pollutant breakpoints

Fully dynamic DAX color rules for each pollutant

Day sorting (Sunday → Saturday)

Glassmorphism UI layout using Power BI visuals

🧠 Tech Stack
Component	Technology
Data Source	WeatherAPI (forecast + aqi)
ETL	Power Query (M Language)
Data Modeling	Power BI
Logic	DAX Measures
Visualization	Power BI (Custom UI + Icons + Cards)
AQI Standard	EAQI (European Air Quality Index)
📡 APIs Used

The dashboard uses:

https://api.weatherapi.com/v1/forecast.json


With parameters:

days=7

aqi=yes

alerts=no

WeatherAPI returns real-time:

Weather

7-day forecast

Air quality (air_quality block)


⭐ Why This Dashboard?

This project demonstrates:

Real API integration inside Power BI

Advanced M scripting

Intelligent DAX color logic

EAQI pollutant categorization

Premium UI/UX design

Multi-state weather forecasting



