📌 Features
GUI built with Tkinter

Fetches live weather data via requests

Displays:

Weather description

Temperature (in °C)

Humidity

Wind speed

Handles errors (invalid city names, network issues)


🧰 Requirements
Python 3.x

Modules:

tkinter (comes with Python)

requests

Install required module (if not already):

bash
Copy code
pip install requests

🔧 Setup & Usage
Clone or download the repository.

Get your free API key from OpenWeatherMap.

Open weather_app.py (or your filename).

Replace this line with your actual key:

python
Copy code
API_KEY = "YOUR_OPENWEATHERMAP_KEY"
Run the app:

bash
Copy code
python weather_app.py
Enter a city name and click "Get Weather".


❗ Troubleshooting
No data returned? Check if your API key is valid and you’re connected to the internet.

Module not found error? Make sure requests is installed.
