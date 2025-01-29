# 🌦️ Weather App

A simple weather application built with **React.js** that fetches real-time weather data using the OpenWeatherMap API.

## 🚀 Features

- 🌍 View the weather of any city worldwide
- 🌞 Dynamic weather icons and background gradients
- ⏳ Displays temperature, humidity, and wind speed
- 🔎 Search by city name
- 📅 Displays the current date

## 🛠️ Technologies Used

- **React.js** (Functional Components, Hooks)
- **CSS** for styling
- **OpenWeatherMap API** for real-time weather data
- **JavaScript Fetch API** for HTTP requests

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/9f3a79d8-8457-4581-bef7-ead12ae66c4d)
*Landing Page, with default location set to Toronto*


![image](https://github.com/user-attachments/assets/25a38201-e427-4a78-aa90-52efa501d60e)
*Example with a different location and weather*

## 🚀 API Key Setup
This project uses the OpenWeatherMap API. To use it:

1. Sign up at OpenWeatherMap and get an API key.
2. Replace the placeholder API key in WeatherApp.js
   ```bash
   const api_key = 'YOUR_API_KEY_HERE';
   ```

## ⚡ Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/KirstenSotelo/WeatherApp
   cd weather-app

2. **Install Dependencies**
   ```bash
   npm install

3. **Run the Development Server
   Make sure you are in the weather-app directory
   ```bash
   npm run dev

4. **Navigate to your Local Host
   Vite will show you a localhost url:
   ```bash
   Local:   http://localhost:5173/
   ```
   Click the link to view the app.


## 📌 Usage
- Type a city name in the search bar and press Enter or click the search icon 🔍.
- The app fetches and displays the weather for the searched location.
- If a city is not found, an error message appears.

##🎯 Future Improvements
- 🌡️ Add a 5-day weather forecast
- 🌎 Display weather for the user's current location
- 📱 Improve UI/UX with more animations
- 📱 Improve Responsiveness
- 📱 Displaying on iPhone
