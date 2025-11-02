# PRODIGY_WD_05

# Weather App 

This is a simple, interactive Weather App built using HTML, CSS, and JavaScript. It retrieves real-time weather information based on the user's current geolocation and displays key details such as:

Temperature

Wind speed

Time of weather report

The app uses the Open-Meteo API to fetch weather data and presents it in a user-friendly format. It also handles cases where geolocation is unavailable or access is denied.

# Features:

Geolocation-based weather data: Automatically fetches the user's current location (latitude and longitude) using the browser's built-in geolocation API.

Real-time data: Displays live weather data including temperature, wind speed, and time of the last weather update.

Responsive Design: The app is simple yet responsive, ensuring it looks good on various screen sizes.

Error handling: The app gracefully handles errors like location access denial and API fetch failures, providing user-friendly messages.

# Technologies Used:

HTML: Structure and content of the page.

CSS: Styling for the page, including a clean layout and responsive design.

JavaScript: Core functionality for fetching and displaying weather data using the browser’s geolocation API and Open-Meteo API.

# How It Works:

The app uses the browser's geolocation API to get the user's current location (latitude and longitude).

It then makes an API call to Open-Meteo to fetch the current weather data for that location.

The weather data (including temperature, wind speed, and time) is displayed in a simple and clean interface.

# Installation:

  To use this app, simply clone this repository to your local machine:

   git clone https://github.com/Yash/Weather-App.git


Open the index.html file in your browser, and the app will start fetching weather data based on your location.
