Weather Application

Overview

This is a simple weather application built with HTML, CSS, and JavaScript. It fetches weather data for a specified city using the OpenWeatherMap API and displays the current weather conditions, including temperature, humidity, and wind speed.

Features

City Search: Allows users to enter a city name to fetch its weather information.
Weather Details: Displays the temperature, humidity, and wind speed for the selected city.
Dynamic Icons: Updates weather icons based on the weather conditions (e.g., rain, clouds, clear sky).
Getting Started

To run this application locally, follow these steps:

Clone the Repository:
git clone <repository-url>
cd <repository-directory>
File Structure: Ensure you have the following files in your project directory:
index.html: Contains the HTML structure and JavaScript functionality.
style.css: CSS file for styling the application.
image/: Directory containing weather-related images (e.g., clouds.png, clear.png, rain.png).
Open in Browser: Simply open the index.html file in a web browser to view and interact with the application.
Code Explanation

HTML
The HTML file includes a search box for entering the city name, a button to trigger the search, and placeholders for displaying weather information and error messages.
Weather details such as temperature, humidity, and wind speed are displayed dynamically based on the API response.
JavaScript
API Key: The API key is used to authenticate requests to the OpenWeatherMap API. Replace "5ee764f111fd6e88a8273497fd6c7ce4" with your own key for production use.
API URL: The base URL for fetching weather data is defined in apiUrl.
Fetching Data: The checkWeather function fetches weather data from the API based on the city name provided, updates the UI with the fetched data, and handles errors (e.g., city not found).
Weather Icons: Depending on the weather conditions, different icons are shown (e.g., clouds, clear sky, rain).
CSS
The CSS file (style.css) is used for styling the application. Ensure you include appropriate styles to make the application visually appealing.
Troubleshooting
Error Handling: If an invalid city name is entered, an error message is displayed.
Empty Search: Ensure that the search box is not empty before clicking the search button.
License

This project is licensed under the MIT License. See the LICENSE file for more details.
