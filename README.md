# Weather App 
This is a simple Python program I built that shows the current weather for any city you type in. It uses the OpenWeatherMap API to fetch real-time data and then displays things like temperature, humidity, wind speed, and a short description of the weather.

# What it does
-You enter the name of a city (e.g., Hyderabad, London, New York).
-It connects to the OpenWeatherMap service.
-It prints out:
  Weather description (like "clear sky" or "light rain")
  Temperature in Celsius
  Humidity percentage
  Wind speed in m/s

# How to run it
-Make sure you have Python 3 installed.
-Install the requests library if you don’t have it yet:
-pip install requests
-We will get our free API key from OpenWeatherMap
-Replace the placeholder in the code with your key:
    API_KEY = "your_api_key_here"

# Run the script:
-python weather.py
-Type a city name when asked, and you’ll see the weather info.
