# 🌤️ Simple Weather App

A minimal and responsive weather web application that lets you check the current weather conditions for any city using the OpenWeatherMap API.


##  Features

- Search for weather by city name  
- Displays temperature, weather condition, and humidity  
- Uses OpenWeatherMap API  
- Responsive layout for mobile and desktop  

##  Tech Stack

- HTML5  
- CSS3  
- JavaScript 
- [OpenWeatherMap API](https://openweathermap.org/api)  

##  How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/farhiamohamed/Weather-app.git
   ```

2. **Navigate to the project folder**  
   ```bash
   cd Weather-app/Simple-Weather-App-master
   ```

3. **Open `index.html` in your browser**  
   You can double-click it or run a local server (optional):  
   ```bash
   # Using Python (optional)
   python3 -m http.server
   ```

## API Key Setup

This app uses the OpenWeatherMap API, which requires an API key.

1. Go to [OpenWeatherMap](https://openweathermap.org/) and sign up.
2. Get your API key from the dashboard.
3. In the `script.js` file, replace `'your_api_key_here'` with your actual API key.

```javascript
const apiKey = "your_api_key_here"; // Replace with your OpenWeatherMap API key
```

## Future Improvements

- Add 5-day forecast  
- Auto-detect user location  
- Dark mode support  
- Error handling for invalid city names  

