# Weather App 🌤️

A user-friendly weather application that provides current weather information for any city. The app uses the OpenWeatherMap API to display temperature, humidity, wind speed, and weather conditions like rain, clouds, snow, and more.

## Demo
Simply enter a city name to get real-time weather information displayed with a clean and intuitive interface.

## Key Features
- 🌎 **City-based Search**: Find weather data for any city across the globe.
- 🌡️ **Real-time Weather Data**: Displays live temperature in Celsius, humidity percentage, and wind speed.
- 🌧️ **Dynamic Weather Icons**: The app changes its icon based on the current weather (e.g., rain, clouds, snow).
- ❌ **Error Handling**: If the city name is invalid, a message is displayed to the user.

## Tech Stack
- **HTML5**: Provides the basic structure of the application.
- **CSS3**: Adds styling and a modern, responsive layout.
- **JavaScript (ES6)**: Handles the core functionality, including fetching data from the API and updating the UI.
- **OpenWeatherMap API**: Used to retrieve live weather data.

## Installation & Setup
To get this project up and running, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd weather-app
    ```

3. **Open `index.html`** in your browser:
    ```bash
    open index.html
    ```

## Usage Instructions
1. Type a city name in the input field.
2. Click the search button or hit `Enter`.
3. The app will fetch and display the current weather data for the city.
4. If the city name is invalid, an error message will appear.

## Configuration
To use the OpenWeatherMap API, you need an API key:

1. Create a free account on [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).
2. Replace the `apiKey` in the `script.js` file with your own API key:
    ```javascript
    const apiKey = "your-api-key-here";
    ```

## Project Structure
```plaintext
├── index.html        # Main HTML file
├── style.css         # Styling for the app
├── script.js         # JavaScript functionality
└── images/           # Icons for weather conditions
