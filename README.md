# Weather App

A simple and beginner-friendly Weather App built using JavaScript, HTML, and CSS. This project provides a hands-on experience with DOM manipulation and demonstrates the use of the Fetch API to retrieve data from the OpenWeatherMap API.

## Features

- **Search Functionality:** Users can enter the name of a city in the search bar.
- **Dynamic Data Fetch:** Utilizes the OpenWeatherMap API to fetch real-time weather data for the specified city.
- **Loading Screen:** Displays a loading screen while waiting for the weather data to be retrieved.
- **Weather Card:** Presents the weather information in a visually appealing card format, including temperature, description, humidity, and wind speed.
- **Background Image:** Enhances user experience with dynamically changing background images based on the searched city, sourced from Unsplash.

## Demo

See the app in action: [Weather App Demo](#) *(Link to be added)*

## How to Use

1. Clone the repository to your local machine.
2. Open `index.html` in a web browser.
3. Enter the name of a city in the search bar and press Enter or click the search button.
4. Explore the real-time weather information displayed on the card.

## Tech Stack

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Project Structure

- **index.html:** Main HTML file for the web page structure.
- **style.css:** Stylesheet for visual presentation and responsiveness.
- **script.js:** JavaScript file for handling dynamic behavior and API interactions.

## Getting Started

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/appid) to enable data fetching.
2. Replace `YOUR_API_KEY` in `script.js` with the obtained API key.

```javascript
let weather = {
    apikey: "YOUR_API_KEY",
    // ... rest of the code
};
```

3. Open `index.html` in a web browser and start exploring the weather app.

Feel free to customize and enhance the app based on your preferences. Happy coding! 🌦️
