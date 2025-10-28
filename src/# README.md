# 🌤️ Weather Now

A simple React app that lets users check the current weather conditions for any city using the *Open-Meteo API*.

---

## 🚀 Features
- Search for any city name  
- Displays temperature and wind speed  
- Uses *Open-Meteo* public API (no key required)

---

## 🧰 Tech Stack
- React (with TypeScript)
- Fetch API
- CSS / Inline styling
- Open-Meteo Geocoding + Forecast API

---

## ⚙️ How It Works
1. User enters a city name  
2. The app fetches latitude & longitude using Open-Meteo Geocoding API  
3. Then it calls Open-Meteo Forecast API to get the current weather  
4. Weather info is displayed instantly

---

## 💻 Run the App Locally
1. Clone or download this sandbox  
2. Run:
   ```bash
   npm install
   npm start