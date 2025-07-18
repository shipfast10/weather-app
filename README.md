🌦️ Weather App
A simple and interactive weather application built using HTML, CSS, and JavaScript, which displays real-time weather information using the OpenWeatherMap API.

🧰 Tech Stack
🌐 HTML – Structure

🎨 CSS – Styling and Layout

⚙️ JavaScript – API Calls and DOM Manipulation

☁️ OpenWeatherMap API – Live weather data

⚙️ Features
🔍 Search weather by city name

🌡️ Displays:

Current temperature

Humidity

Wind speed

Atmospheric pressure

Current date

📸 Dynamic weather icons (Cloudy, Clear, Rain, etc.)

❌ Error handling for invalid city input

🚀 How to Run Locally
1. Clone the Repository

git clone https://github.com/your-username/weather-app.git
cd weather-app

2. Set Up API Key
Create an account on https://openweathermap.org

Generate your API key

Replace the API key in script.js:

const apiKey = "YOUR_API_KEY_HERE";

3. Open index.html
You can simply double-click index.html or use Live Server in VS Code.

📁 Project Structure

weather-app/
├── images/
│   ├── clouds.png
│   ├── clear.png
│   ├── drizzle.png
│   ├── rain.png
│   └── mist.png
├── style.css
├── script.js
├── index.html
└── README.md

🧠 How It Works
Listens for the click or keypress event on the search input/button.

Fetches weather data using the OpenWeatherMap API for the entered city.

Parses and displays weather details on the screen.

Changes weather icon based on condition (e.g., Clear, Rain, etc.).

Handles city not found error (status 404) and shows a custom error message.

📄 License
This project is open-source and available under the MIT License.