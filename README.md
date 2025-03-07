# Weather App

Welcome to the **Weather App**! This is a simple and user-friendly weather application built using **Flutter**. It allows users to check the current weather conditions and hourly forecasts for any location using the **OpenWeatherMap API**.

---

## Features

### 1. **Current Weather**
- Displays the current temperature in Celsius.
- Shows the current weather condition (e.g., Clear, Cloudy, etc.).
- Includes a refresh button to update the weather data.

### 2. **Hourly Forecast**
- Provides weather forecasts at 3-hour intervals.
- Displays temperature and weather conditions for each interval.

### 3. **Additional Information**
- Current **humidity** percentage.
- Current **wind speed** in meters per second.
- Current **pressure** in hPa.

---

## Screenshots

[![Watch the video](https://raw.githubusercontent.com/yash2895/weather_app/main/screenshot1.png)](https://raw.githubusercontent.com/yash2895/weather_app/main/movie.mp4)


---

## Installation

Follow these steps to run the app on your local machine:

### Prerequisites:
1. Flutter SDK installed on your system. [Install Flutter](https://flutter.dev/docs/get-started/install)
2. OpenWeatherMap API Key. [Get your API Key](https://openweathermap.org/api)

### Steps:
1. Clone this repository:

        git clone https://github.com/yash2895/weather_app.git

2. Navigate to the project directory:

        cd weather_app

3. Install dependencies:

        flutter pub get

4. Create a dart file called secrets.dart and then paste the following command and replace Your_API_Key with your own API key

        const openWeatherAPIKey = 'Your_API_Key';

5. Run the app:

        flutter run


---

## Technologies Used

- **Flutter**: Framework for building cross-platform applications.
- **Dart**: Programming language used with Flutter.
- **OpenWeatherMap API**: Provides weather data for locations worldwide.

---

## Future Improvements

Here are some features that could be added in future versions:
1. Search functionality to find weather by city name.
2. Support for multiple units (Celsius, Fahrenheit, Kelvin).
3. Weekly forecast display.
4. Dark mode support.

---

## Feedback & Contributions

Feel free to open issues or submit pull requests if you have suggestions or improvements for this project!

---

Thank you for checking out the Weather App! 😊

---
