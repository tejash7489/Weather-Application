# Weather-Application
know about weather condition by giving access of your current location or by entering any of the locations name
🌦 Weather Information Feature

Our platform allows users to easily check real-time weather conditions for any location. This feature can be used in two ways:

📍 Using Your Current Location

With your permission, the browser automatically fetches your latitude and longitude using the Geolocation API.

Weather data is then retrieved for your exact position.

📝 Searching by Location Name

Simply enter the name of a city or location in the search bar.

The system fetches weather details for that location instantly.

🔍 Details Provided:

🌡 Temperature (in °C/°F)

🌥 Weather Condition (Clear, Cloudy, Rainy, etc.)

💨 Wind Speed

💧 Humidity

📅 Date & Time of the report

🛠 How It Works:

Frontend: Built using React, uses the Geolocation API for detecting current location and fetch API for calling weather services.

Weather API: Integrated with OpenWeatherMap API (or any API you used) to fetch real-time weather details.

User Choice: Either allow location access or manually enter a city name.
