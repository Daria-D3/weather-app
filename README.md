# Weather App ☀️

**A clean and intuitive weather application that provides current weather conditions and hourly forecasts for any city worldwide.**

<img width="2304" height="1333" alt="image" src="https://github.com/user-attachments/assets/8c1204d1-3fa0-49c3-a910-6b04c9f3f0a0" />


## 🌟 Features

- **City Search** - Look up weather for any city globally
- **Current Weather** - Display real-time temperature, conditions, and weather icons
- **Hourly Forecast** - View the next 24 hours of weather data (8 data points)
- **Dynamic Weather Icons** - Visual representation of weather conditions
- **Keyboard Support** - Press Enter to search for quick access
- **Smooth Animations** - Bouncing title and fade-in effects using Animate.css
- **Glass Morphism Design** - Modern frosted glass UI with backdrop blur effects

## 🛠️ Tech Stack

- **HTML5** - Structure and markup
- **CSS3** - Styling with glassmorphism effects and animations
- **JavaScript (Vanilla)** - API integration and dynamic content
- **OpenWeatherMap API** - Weather data provider
- **Animate.css** - Animation library

## 🚀 Live Demo

Check out the live site: [Weather App](https://daria-d3.github.io/weather-app/)

## 📋 How It Works

1. Enter a city name in the search box
2. Click "Search" or press Enter
3. View current temperature in Celsius with weather description
4. Scroll through hourly forecast for the next 24 hours
5. See dynamic weather icons that match current conditions

## 🔑 API Integration

This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch:
- Current weather data (`/weather` endpoint)
- 5-day forecast data (`/forecast` endpoint)

Temperature is automatically converted from Kelvin to Celsius for display.


## 📁 Project Structure

```
weather-app/
├── index.html       # Main HTML structure
├── style.css        # Styling and animations
└── script.js        # Weather API logic and DOM manipulation
```

## ✨ Key Features Implementation

- **Error Handling** - Alerts for invalid city names or API errors
- **Responsive Design** - Works on various screen sizes
- **Temperature Conversion** - Automatic Kelvin to Celsius conversion
- **Dynamic Updates** - Real-time DOM manipulation
- **Horizontal Scroll** - Hourly forecast cards with smooth scrolling

## 🎨 Design Highlights

- Purple gradient background (#8C52FF)
- Glassmorphism container with blur effects
- Clean, centered layout
- Smooth hover effects on buttons
- Animated weather icons from OpenWeatherMap

## 🎯 Future Enhancements

- Add 5-day forecast view
- Toggle between Celsius and Fahrenheit
- Geolocation support for automatic city detection
- Weather alerts and notifications
- Save favorite cities
- Dark/light theme toggle
- More detailed weather metrics (humidity, wind speed, pressure)

## 📄 License

This project was created as a portfolio piece for learning web development and API integration.

---

**Weather App** - *Simple, clean, and accurate weather at your fingertips* 🌤️
