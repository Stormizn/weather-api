# Weather App

A Flask web application that displays current weather for any city using the OpenWeatherMap API.

## Features

- Search current weather by city name
- Shows temperature (metric) and weather description
- Clean, responsive UI with gradient background
- Error handling for invalid city names

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS (Jinja2 templating)
- **API**: OpenWeatherMap

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install flask requests
   ```
3. Run the app:
   ```bash
   python app.py
   ```
4. Open `http://127.0.0.1:5000` in your browser

## Usage

Enter a city name in the input field and click "Check Weather" to see the current temperature and conditions.
