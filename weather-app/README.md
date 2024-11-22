# Weather App

## Description  
This Weather App is a simple and interactive application that provides real-time weather updates for any location. Built with **Vanilla JavaScript**, **HTML**, and **CSS**, the app fetches data from the [OpenWeather API](https://openweathermap.org/api) to display the current weather conditions, temperature, humidity, wind speed, and more.

---

## Features  
- **Real-Time Weather Data**: Fetches and displays live weather data from the OpenWeather API.  
- **Search by City**: Users can enter the name of any city to get its current weather.  
- **Dynamic Icons**: Weather icons update dynamically based on the current weather conditions.  

---

## Technologies Used  
- **HTML**: For structuring the layout of the app.  
- **CSS**: For styling and responsiveness.  
- **JavaScript**: For fetching API data and dynamically updating the UI.  

---

## Installation  

### Prerequisites  
- A modern web browser.  
- A free API key from [OpenWeather API](https://openweathermap.org/api).  

### Steps  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/Ignatius-Nobel/weather-app.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd weather-app  
   ```  
3. Open the `index.html` file in your browser.  

---

## Usage  
1. Enter the name of a city in the search box.  
2. Press the **Search** button.  
3. View the weather details for the selected location.  

---

## Configuration  
To fetch data from the OpenWeather API, you'll need to replace the placeholder `API_KEY` in your JavaScript code with your actual API key.  

Locate the following line in bottom of `index.html`:  
```javascript  
const apiKey = 'your_api_key_here';
```  
Replace `'your_api_key_here'` with your OpenWeather API key.  

---
