
# Weather App

This is a simple weather application built using HTML, CSS, and JavaScript. The app uses the [OpenWeather API](https://openweathermap.org/api) to fetch real-time weather data for any city entered by the user.

## Features

- Search for weather information by city name.
- Displays the current temperature, weather condition, humidity, wind speed, and more.
- Dynamic background change based on weather conditions.
- Responsive design, optimized for both desktop and mobile devices.

## Technologies Used

- **HTML5**: Structure of the app.
- **CSS3**: Styling for the app, including responsive layout.
- **JavaScript (ES6)**: Core functionality, fetching data from the OpenWeather API.
- **OpenWeather API**: Provides real-time weather data.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/brijgopal03/WeatherApp.git
    ```
2. Navigate to the project directory:
    ```bash
    cd WeatherApp
    ```
3. Open `index.html` in your web browser to view the app.

4. Give the location permission to automatically get the current weather information.

## API Setup

To use the OpenWeather API, you need to create a free account and get an API key. Follow these steps:

1. Sign up at [OpenWeather](https://home.openweathermap.org/users/sign_up).
2. Create an API key from the dashboard.
3. In the project, replace `'YOUR_API_KEY'` in the JavaScript file with your actual API key.

```javascript
const apiKey = 'YOUR_API_KEY';
```
