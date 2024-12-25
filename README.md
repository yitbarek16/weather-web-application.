# weather-web-application.
Weather App: A Django web app that provides real-time weather updates for any city using the OpenWeatherMap API. Displays temperature, weather conditions, and an icon with a clean, responsive interface.

## Features
- 🏙️ Search for current weather conditions in any city.
- 🌡️ Displays temperature, weather description, and an icon.
- 🔐 Handles API errors gracefully with default data and error messages.
- 📱 Responsive design using Bootstrap for a modern and clean user interface.

---

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (via Bootstrap)
- **API Integration**: OpenWeatherMap API
- **Tools**: Requests library for API calls

---

## Prerequisites
Before running the application, ensure you have the following installed:
- Python 3.x
- Django 3.x or later
- An active API key from [OpenWeatherMap](https://openweathermap.org/).

---

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   
2. **Create and activate a virtual environment**:
     ```bash
     python -m venv venv
     source venv/bin/activate

3. **Add your OpenWeatherMap API key**:
   url = 'https://api.openweathermap.org/data/2.5/weather?q={}&units=metric&appid=YOUR_AP

4. **Run database migrations**:
     ```bash
     python manage.py migrate

5. **Start the development server**:
     ```bash
     python manage.py runserver
     
6. **Access the application**:
     Open your web browser and navigate to http://127.0.0.1:8000/.
