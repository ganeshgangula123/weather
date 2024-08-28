Project Name: Weather Data Fetching Web Page
Overview:
      This project involves building a dynamic web page that fetches and displays weather data based on the user's location or a user-inputted location. The web page will   provide real-time weather information including current weather conditions, temperature. This will be achieved by integrating with a weather API.

Objectives
      User Location-Based Weather Data: Automatically fetch weather data based on the user's geographical location using the browser's geolocation API.
    
User-Inputted Location: 
      Allow users to manually input a location (city name) to fetch and display weather data for that specific area.
    Display Weather Information: Present the current weather conditions, temperature, humidity, and wind speed in a user-friendly and visually appealing format.
    
Technologies Used:
      HTML: For structuring the web page.
      CSS: For styling the web page and ensuring a responsive and visually appealing design.
      JavaScript: For fetching weather data from the API and dynamically updating the web page content.
      Weather API: OpenWeatherMap API to retrieve real-time weather data.
Features:
      Geolocation Weather Fetching:
      Automatically detect the user's location.
      Fetch and display the current weather data based on the detected location.
      Manual Location Input:
      Provide an input field for users to enter a city name.
      Fetch and display the weather data for the user-inputted location.
      Weather Information Display:
      Show the city name and country.
      Display the current weather condition (e.g., clear sky, rain, etc.).
      Present the temperature in Celsius.
      Show humidity levels and wind speed.
Implementation Steps:

HTML Setup:
        Create a basic structure with a title, input field for location, and a button to fetch weather data.
      Include a section to display the fetched weather information.
CSS Styling:
        Style the input field, button, and weather information display for a clean and user-friendly interface.
JavaScript Functionality:
        Write functions to fetch weather data from the OpenWeatherMap API.
      Implement geolocation functionality to detect and use the user's location.
      Update the web page dynamically with the fetched weather data.
      
API Integration:
        Sign up for an API key from OpenWeatherMap.
       Use the API key to make requests and retrieve weather data.
       
Example Usage:
        When a user visits the web page, they can either allow the browser to access their location or manually enter a city name.
      The web page will fetch and display the current weather data for the detected or entered location.
      Users will be able to see information like the current weather condition, temperature, humidity, and wind speed, presented in an easy-to-read format.
      This project will provide a practical and interactive way for users to access real-time weather information, leveraging modern web technologies and APIs.
