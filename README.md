# Weather Forecast Web App

## Description

This is a simple Weather Forecast web application built using HTML, CSS, and JavaScript. It utilizes a weather API to provide users with up-to-date weather information for a specified location. Users can enter a city name or ZIP code, and the app will fetch and display the current weather conditions along with a 5-day forecast.

## Features

- **Current Weather**: Provides the current weather conditions for the specified location, including temperature, humidity, wind speed.

- **Search by Location**: Allows users to search for weather information by entering a city name or ZIP code.

## Technologies Used

- HTML: The structure of the web page is built using HTML.

- CSS: Styling and layout are done using CSS.

- JavaScript: Used to fetch data from the weather API, manipulate the DOM, and handle user interactions.

- [Weather API](https://weatherapi.com/): This app relies on the Weather API to fetch weather data. You will need to obtain an API key from the Weather API website to use this app.

## Installation

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/yourusername/weather-forecast.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-forecast
   ```

3. Open the `index.html` file in your preferred web browser.

## Usage

1. Open the web app by opening the `index.html` file in a web browser.

2. Enter a city name or ZIP code in the search bar and click the "Search" button or press Enter.

3. The app will fetch and display the current weather conditions and a 5-day forecast for the specified location.

4. To clear the search results and search for a new location, click the "Clear" button.

## Configuration

Before using this application, you need to obtain an API key from the [Weather API](https://weatherapi.com/) website.

1. Visit the Weather API website and sign up for an account if you don't have one.

2. After signing in, navigate to the API section and create a new API key.

3. Copy your API key and replace the placeholder in the `script.js` file with your actual API key:

   ```javascript
   const apiKey = 'YOUR_API_KEY_HERE';
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the Weather API for providing weather data, and to the Weather Icons project for their weather icons.

---

Feel free to contribute, report issues, or make suggestions for improvement. Enjoy using the Weather Forecast web app!
