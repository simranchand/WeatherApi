# 🌤️ Weather API Web App

A simple and responsive weather application that fetches real-time weather data using the **OpenWeatherMap API**. Users can enter any city name to view current weather conditions, including temperature, humidity, wind speed, and a dynamic weather icon.

---

## 📷 Screenshot
<img width="660" height="274" alt="WEATHER_API_SS_1" src="https://github.com/user-attachments/assets/d92c8094-3983-4fac-85f6-4fc3e8436d63" />
<img width="697" height="737" alt="WEATHER_API_SS_2" src="https://github.com/user-attachments/assets/9b9fad4d-eb40-4660-bb55-c2af0eda9830" />
<img width="646" height="338" alt="WEATHER_API_SS_3" src="https://github.com/user-attachments/assets/563b8b57-88e9-41aa-89c6-bb683ecf595a" />


---

## 🚀 Features
- 🔍 Search weather by city name
- 🌡️ Display current temperature in Celsius
- 💧 Shows humidity and wind speed
- 🌤️ Dynamic weather icons based on conditions
- ⚠️ Error message for invalid city input
- 📱 Fully responsive design using pure HTML and CSS

---

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
- [OpenWeatherMap API](https://openweathermap.org/api)

---

## 📦 Folder Structure
WeatherApi/
│
├── index.html
├── style.css
├── script.js (embedded in HTML)
├── images/
│ ├── clear.png
│ ├── clouds.png
│ ├── drizzle.png
│ ├── mist.png
│ ├── rain.png
│ ├── humidity.png
│ ├── wind.png
│ └── search.png


---

## 🔐 API Key
This project uses a free API key from OpenWeatherMap:
```js
const apiKey = "your_api_key_here";

🧠 How It Works
User enters a city name.

The app sends a request to OpenWeatherMap API with that city.

If valid, it fetches weather data and updates the UI.

If not, an error message is shown.

🧑‍💻 Author
Simran Chand
GitHub: @simranchand

📜 License
This project is open-source and free to use.

✅ Future Improvements
Add loading animation

Support for geolocation (current location weather)

5-day weather forecast

Theme toggle (light/dark mode)
