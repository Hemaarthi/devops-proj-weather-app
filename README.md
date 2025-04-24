# 🌤️ Weather App

This is a simple and responsive weather web application that allows users to search for the current weather conditions of any city using the [Weatherstack API](https://weatherstack.com/).

## 🚀 Features

- Search for real-time weather using city name
- Displays:
  - Current temperature
  - City name
  - Humidity
  - Wind speed
  - Weather icon based on conditions
- Responsive design for mobile and desktop views

## 🛠️ Built With

- HTML
- CSS
- JavaScript (Vanilla)
- [Weatherstack API](https://weatherstack.com/)

## 📸 Demo

![App Screenshot](images/screenshot.png) <!-- Replace this with your actual screenshot path -->

## 📦 Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/weather-app.git
    cd weather-app
    ```

2. Open `index.html` in your browser:
    ```bash
    start index.html # On Windows
    open index.html  # On macOS
    ```

## 🔑 API Key

This app uses Weatherstack for real-time weather data. You need to get your own API key from [weatherstack.com](https://weatherstack.com/) and replace the `apikey` variable in the script tag of `index.html`.

```js
const apikey = "YOUR_API_KEY";
