# City Direction & Distance Finder (`CityLocationFinder`)

[![Web API](https://img.shields.io/badge/Browser_API-Geolocation_%2B_DeviceOrientation-0082FC)](#features)
[![i18n](https://img.shields.io/badge/i18n-EN_%7C_KO_%7C_JA_%7C_ZH_%7C_ES-10A37F)](#features)

A zero-dependency, multi-lingual web utility that calculates great-circle distance (Haversine formula) and real-time compass bearing from the user's live GPS coordinates to global cities or custom latitude/longitude targets.

## Features

*   **Geolocation:** Automatically fetches your current location.
*   **City Selection:** Choose from a list of countries and cities, or enter custom coordinates.
*   **Real-time Compass:** A compass that shows your current orientation and the direction of the target city.
*   **Multi-language Support:** The interface is available in English, Korean, Japanese, Chinese, and Spanish.
*   **Responsive Design:** Works on both desktop and mobile devices.

## How to Use

1.  Open the `index.html` file in your web browser.
2.  Allow the browser to access your location.
3.  Select a country and a city from the dropdown menus.
4.  The application will display the distance and direction to the selected city.

## File Structure

*   `index.html`: The main HTML file.
*   `css/style.css`: Contains all the styles for the application.
*   `js/data.js`: Contains the translation strings and city data.
*   `js/ui.js`: Functions for updating the user interface.
*   `js/location.js`: Functions for handling geolocation and calculations.
*   `js/compass.js`: Functions for the compass and device orientation sensors.
*   `js/main.js`: The main script that initializes the application.