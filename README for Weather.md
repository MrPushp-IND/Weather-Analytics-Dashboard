# 🌤️ Weather Analytics Dashboard

A modern, responsive **Weather Analytics Dashboard** built with **HTML, CSS, and JavaScript**, powered by the **Open-Meteo API**.

The dashboard allows users to search for any city or location and automatically retrieves its geographical coordinates and live weather data—so there is no need to manually enter latitude and longitude.

## 🚀 Features

- 📍 **Location Search**
  - Search by city, district, or country
  - Automatically converts the location into latitude and longitude

- 🌡️ **Current Weather**
  - Temperature
  - Feels-like temperature
  - Relative humidity
  - Precipitation
  - Cloud cover
  - Wind speed
  - Wind direction
  - Atmospheric pressure

- 📈 **24-Hour Weather Analytics**
  - Temperature trend
  - Feels-like temperature
  - Humidity
  - Cloud cover
  - Precipitation probability
  - Wind speed
  - Wind gusts

- 📅 **7-Day Forecast**
  - Daily weather conditions
  - Maximum temperature
  - Minimum temperature
  - Rain probability
  - Precipitation
  - Maximum wind speed

- 📊 **Interactive Charts**
  - Powered by Chart.js
  - Responsive visualizations

- 🧠 **Automated Weather Insights**
  - Temperature analysis
  - Rain probability analysis
  - Wind condition analysis
  - Average humidity analysis

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Dashboard structure |
| CSS3 | Styling and responsive layout |
| JavaScript | Data fetching and dashboard logic |
| Chart.js | Interactive charts |
| Open-Meteo Geocoding API | Location search |
| Open-Meteo Forecast API | Weather data |

## 🔄 How It Works

```text
User enters location
        ↓
Open-Meteo Geocoding API
        ↓
Latitude & Longitude retrieved
        ↓
Open-Meteo Forecast API
        ↓
Weather data retrieved
        ↓
JavaScript processes the data
        ↓
Dashboard updates automatically
```

## 📁 Project Structure

```text
weather-analytics-dashboard/
│
├── index.html
└── README.md
```

The current version is a single-page HTML application containing the HTML, CSS, and JavaScript in one file.

## ▶️ Run Locally

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/weather-analytics-dashboard.git
```

2. Open the project folder.
3. Open `index.html` in your browser.
4. Enter a location such as `Greater Noida`, `Delhi`, `Mumbai`, or `London`.
5. Click **Get Weather**.

## 🌐 API

This project uses **Open-Meteo**:

- Geocoding API — converts location names into coordinates
- Forecast API — provides current, hourly, and daily weather data

No API key is required for the implementation used in this project.

## 📊 Dashboard Sections

### Current Weather
Displays the selected location's latest weather conditions and key meteorological indicators.

### 24-Hour Analytics
Provides visual analysis of temperature, humidity, precipitation probability, and wind conditions.

### 7-Day Forecast
Displays a daily forecast table with temperature, precipitation, and wind information.

### Automated Insights
Generates simple observations based on forecast temperature, precipitation probability, wind speed, and average humidity.

## 📱 Responsive Design

The dashboard is designed for:

- 💻 Desktop
- 💻 Laptop
- 📱 Tablet
- 📱 Mobile

## 🔮 Future Improvements

- 🌍 Interactive weather map
- 📍 Browser-based current-location detection
- 🌙 Dark mode
- 🌧️ Detailed hourly precipitation charts
- 🌅 Sunrise and sunset information
- 🗺️ Multiple-location comparison
- 📊 Historical weather analytics
- 🔔 Weather alerts
- 📈 Advanced weather insights
- ☁️ Cloud deployment

## 👨‍💻 Author

**Pushp Raj**

PGDM — Business Analytics & HR

Interested in **Business Analytics, Data Analytics, AI, Machine Learning, and Business Intelligence**.

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

## 📌 Data Source

Weather data provided by **Open-Meteo**.

This project is intended for educational, analytics, and demonstration purposes.
