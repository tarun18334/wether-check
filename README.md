
# 🌤️ Weather App

A simple and stylish weather web application built with **HTML**, **CSS**, and **JavaScript**. It fetches real-time weather data using the [OpenWeatherMap API](https://openweathermap.org/api) and displays key information like temperature, humidity, wind speed, and a weather condition icon.

---

## 🔍 Features

- Search for current weather by city name
- Real-time temperature (in °C), wind speed, and humidity
- Weather icons based on current conditions (Rain, Clear, Clouds, etc.)
- Error message for invalid city names
- Responsive and modern UI design

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (with gradient backgrounds and responsive layout)
- JavaScript (Fetch API for asynchronous API calls)
- OpenWeatherMap API

---

## 📁 Project Structure
weather-app/
├── index.html # Main HTML structure
├── style.css # Styling for the app
├── script.js # Logic for fetching and displaying weather data
└── img/ # Folder for weather icons (e.g., rain.png, clear.png)


---

## 🚀 How to Run

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Type a city name and click the search button 🔍.

---

## 📸 Screenshots

<img width="1642" height="551" alt="image" src="https://github.com/user-attachments/assets/cfb33cab-793b-4b21-96e2-1d90ce210c2b" />

<img width="1678" height="951" alt="image" src="https://github.com/user-attachments/assets/18fe13e2-becb-4576-bc2b-abbc95a6320c" />



---

## 📌 Note

- Make sure to replace the API key in `script.js` with your own from [OpenWeatherMap](https://openweathermap.org/api) if you hit rate limits.
- Example in `script.js`:
  ```javascript
  const apiKey = "YOUR_API_KEY_HERE";

