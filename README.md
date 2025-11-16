🌤️ Power BI Weather & Air Quality (EAQI) Dashboard

A modern, mobile-app–style Weather + Air Quality Dashboard built using Power BI, WeatherAPI, and EAQI (European Air Quality Index) standards.

This dashboard visualizes real-time weather, 7-day forecasts, and detailed air-quality pollutants such as PM2.5, PM10, NO₂, SO₂, O₃, and CO using dynamic UI, icons, and intelligent DAX measures.

📌 Features
🌦️ Weather Insights

Real-time temperature, humidity, and wind speed

Weather condition icons (auto-fetched from API)

Feels-like temperature

Sunrise & Sunset visualization

Chance of Rain (visual container)

7-day forecast with temperature, UV, rain, icons

🏭 Air Quality Insights (EAQI Standard)

Includes live monitoring of:

PM2.5

PM10

NO₂

SO₂

O₃

CO

With:

EAQI-based pollutant levels

Dynamic DAX color indicators

Health-based severity categories

🛠️ Technical Highlights

Automated WeatherAPI integration via Power Query (M code)

7-day forecast extracted for multiple Indian states

Optimized data model and transformations

EAQI-compliant pollutant breakpoints applied

Fully dynamic DAX color logic for each pollutant

Custom day sorting (Sunday → Saturday)

Premium glassmorphism UI design in Power BI

🧠 Tech Stack
Component	Technology
Data Source	WeatherAPI (Forecast + AQI)
ETL	Power Query (M Language)
Data Modeling	Power BI
Intelligence	DAX Measures
Visualization	Power BI (Custom UI + Icons + Cards)
AQI Standard	EAQI (European Air Quality Index)
📡 API Used

WeatherAPI Forecast Endpoint:

https://api.weatherapi.com/v1/forecast.json


Parameters

days=7

aqi=yes

alerts=no

WeatherAPI returns:

Live weather (current)

7-day forecast (forecastday[])

Full pollutant breakdown (air_quality{})

🧪 EAQI Breakpoints Used
PM2.5 (µg/m³)
Level	Range
Good	0–10
Fair	10–20
Moderate	20–25
Poor	25–50
Very Poor	50–75
Extremely Poor	75+
PM10 (µg/m³)
Level	Range
Good	0–20
Fair	20–35
Moderate	35–50
Poor	50–100
Very Poor	100–150
Extremely Poor	150+

(Similar pollutant tables apply for NO₂, SO₂, O₃, and CO.)

📁 Project Structure
📦 Weather-AQI-Dashboard
 ┣ 📄 india_weather_aqi_dashboard.pbix
 ┣ 📄 powerquery_script.m
 ┣ 📄 dax_measures.txt
 ┣ 📂 screenshots
 ┃ ┗ 📸 dashboard.png
 ┗ 📄 README.md

📊 Dashboard Preview

(Add your dashboard screenshot here)

Example:


🔄 Automatic Refresh

When published to Power BI Service:

✔ Supports Daily Scheduled Refresh

✔ Refresh multiple times per day (Pro/Premium)

✔ WeatherAPI fetches data automatically during each refresh

🚀 How to Use the Dashboard

Clone or download this repository

Open the .pbix file in Power BI Desktop

Add your WeatherAPI key inside Power Query

Refresh the dashboard

(Optional) Publish to Power BI Service for automatic updates

⭐ Why This Dashboard Stands Out

This project demonstrates:

Real-world API integration inside Power BI

Advanced Power Query (M code) scripting

Intelligent and dynamic DAX color logic

EAQI-compliant pollutant analysis

Stunning mobile-app-like UI

Multi-state 7-day weather forecasting

Perfect for:

Portfolios

Data analytics resumes

GitHub projects

Dashboard engineering showcases

👨‍💻 Author

Vansh Yadav
BTech Student | GenAI & Data Analytics Intern
Passionate about Weather Intelligence, Power BI, and Modern Data Visualization.

🙌 Contributions

Feel free to open issues, suggest improvements, or submit pull requests.

