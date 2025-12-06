# Weather-App

🌦️ Weather App

A simple, clean, and responsive Weather Application built using HTML, CSS, and JavaScript.
It fetches real-time weather data using the OpenWeatherMap API and displays the temperature, humidity, wind speed, and weather condition icon for any city the user searches.

🚀 Features

🔍 Search weather by city name

🌡️ Displays real-time temperature (°C)

💧 Shows humidity levels

🌬️ Wind speed converted automatically to Km/hr

🌤️ Dynamic weather icons

⚠️ Error message for invalid city names

⌨️ Supports Enter key for quick search

📱 Responsive design using CSS

📸 Preview

The interface includes:

A search bar with button

Temperature & city display

Weather icon that changes based on conditions

Humidity & Wind details section

(Add screenshots here if you want)

🛠️ Technologies Used

HTML5 — structure

CSS3 — responsive UI & styling

JavaScript (Vanilla JS) — API handling & interactivity

OpenWeatherMap API — real-time weather data

📦 Installation & Setup

Clone the repository:

git clone https://github.com/your-username/weather-app.git


Open the project folder:

cd weather-app


Open the app:

Simply open index.html in your browser.
No build tools or servers needed.

🔑 API Key Setup

This project uses the OpenWeatherMap API.

Inside your index.html, the API key is referenced here:

const apiKey = "YOUR_API_KEY_HERE";


Replace "YOUR_API_KEY_HERE" with your actual API key from:
👉 https://openweathermap.org/api

📁 File Structure
/
├── index.html        # Main app layout & JavaScript logic
├── style.css         # Styling for the UI
└── images/           # Weather icons (clouds, rain, humidity, wind, etc.)

💡 How It Works

User enters a city name.

A request is sent to the OpenWeatherMap API:

https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={API_KEY}


If the city exists → weather info is displayed.

If not → an error message shows (“Invalid city name”).

Weather icons change based on conditions:

Clouds

Rain

Drizzle

Mist

🐞 Known Improvements (Optional)

Add icons for more weather conditions (snow, clear sky, storm)

Add geolocation to detect user's current weather

Add 5-day forecast

Add light/dark theme toggle
