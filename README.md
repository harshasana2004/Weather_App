🌤 Weather App
A sleek and responsive weather application built using HTML, CSS, and JavaScript, powered by the OpenWeatherMap API.
This app allows users to search for any city and instantly view current weather details, including temperature, humidity, wind speed, and weather conditions with corresponding icons.

📌 Features
🔍 City Search – Enter any city name to get live weather data.
🌡 Temperature Display – Shows the current temperature in Celsius.
💧 Humidity Levels – Displays current humidity percentage.
🌬 Wind Speed – Shows wind speed in km/hr.
🎨 Responsive Design – Works on desktop and mobile devices.
📷 Dynamic Weather Icons – Changes based on weather condition (Cloudy, Rainy, Sunny, Misty, etc.).
⚠ Error Handling – Displays a friendly error message if the city is not found.


📂 Project Structure
Weather-App/
│
├── index.html         # Main HTML file
├── style.css          # Stylesheet
├── images/            # Weather icons and search button image
│   ├── search.png
│   ├── clouds.png
│   ├── rain.png
│   ├── clear.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   └── wind.png
└── README.md          # Project documentation


⚙️ How It Works
User enters a city name and clicks the search button.
The app sends a request to the OpenWeatherMap API.
If the city exists, weather details are displayed; otherwise, an error message appears.
Weather icons change dynamically based on the current weather condition.

🛠 Technologies Used
HTML5 – Structure
CSS3 – Styling & Layout
JavaScript (ES6) – Logic & API Calls
OpenWeatherMap API – Weather Data
