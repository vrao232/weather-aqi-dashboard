# 🌤️ Power BI Weather & Air Quality (EAQI) Dashboard

A modern, mobile-app–style **Weather + Air Quality Dashboard** built using **Power BI**, **WeatherAPI**, and **EAQI (European Air Quality Index)** standards.

This dashboard visualizes **real-time weather**, **7-day forecasts**, and detailed **air-quality pollutants** such as **PM2.5, PM10, NO₂, SO₂, O₃, and CO**, using dynamic UI elements, icons, and intelligent DAX measures.

---

## 📌 Features

### 🌦️ Weather Insights
- Real-time **temperature**, **humidity**, and **wind speed**
- Weather condition icons (auto-fetched from WeatherAPI)
- **Feels-like** temperature
- **Sunrise & Sunset** visualization
- **Chance of Rain** with circular rain indicator
- Full **7-day forecast** (Temp, Rain, UV, Icons)

### 🏭 Air Quality Insights (EAQI Standard)
Monitors:
- PM2.5  
- PM10  
- NO₂  
- SO₂  
- O₃  
- CO  

Includes:
- EAQI pollutant level classification  
- Color-coded severity indicators  
- Dynamic DAX-based pollutant categories  

### 🛠️ Technical Highlights
- Automated **WeatherAPI** integration (M Script)
- 7-day forecast for **multiple Indian states**
- Clean, optimized data transformations
- **EAQI-compliant** pollutant breakpoints applied
- Fully dynamic **DAX color rules**
- Custom **day sorting (Sunday → Saturday)**
- Premium **Glassmorphism UI layout**

---

## 🧠 Tech Stack

| Component | Technology |
|----------|------------|
| Data Source | WeatherAPI (Forecast + AQI) |
| ETL | Power Query (M Language) |
| Modeling | Power BI |
| Logic Layer | DAX Measures |
| Visuals | Power BI Cards, Charts, Icons |
| AQI Standard | EAQI (European Air Quality Index) |

---

## 📡 API Used

**WeatherAPI Forecast Endpoint**


