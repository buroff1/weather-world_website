# WeatherWorld Website 🌦️

## 📝 Content

- [Overview](#overview)
- [Technologies](#technologies)
- [Features](#features)
- [Project Structure](#%EF%B8%8Fproject-structure)
- [Run Project](#run-project)
- [Managing API Keys](#managing-api-keys)
- [Contributing](#contributing)
- [Contact](#contact)

## 🗺️Overview

The WeatherWorld Website is a web-based application that provides real-time weather updates and forecasts for locations around the world. Utilizing the OpenWeatherMap API Developer Plan, it delivers detailed weather information through a user-friendly interface.

## 👨‍💻Technologies

- **Python**: The core programming language used for development.
- **Flask**: A lightweight WSGI web application framework.
- **Bootstrap5**: Front-end framework for developing responsive and mobile-first websites.
- **SQLite**: Database for storing user and system data.
- **Flask-Migrate**: Handles database migrations.
- **Flask-SQLAlchemy**: Adds SQLAlchemy support for Flask applications.
- **Requests**: Library to handle HTTP requests.

## 👀Features

- **Real-Time Weather Data**: Access up-to-date weather information.
- **Forecasting**: Get hourly and weekly weather forecasts.
- **User-Friendly Interface**: Easy navigation and responsive design.
- **Environmental Awareness**: Includes UV index information.

## 🗃️Project Structure

- `app.py`: Main Flask application file with routes.
- `models.py`: Defines database models.
- `templates/`: Folder containing HTML templates for the website.
- `static/`: Contains CSS, JavaScript, and image files.
- `.env`: Environment variables for configuration settings.
- `requirements.txt`: Required Python packages.

## ✅Run Project

1. **Clone the repository**:
```
git clone https://github.com/buroff1/WeatherWorld-website.git
cd WeatherWorld-website
```
2. **Set up a virtual environment**:
```
python3 -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate
```
3. **Install dependencies**:
```
pip install -r requirements.txt
```
4. **Set environment variables**:
Set the `SECRET_KEY` and `OPENWEATHERMAP_API_KEY` in your operating system's environment variables or through your IDE for development.
```
export SECRET_KEY='your_secret_key_here'
export OPENWEATHERMAP_API_KEY='your_openweathermap_api_key_here'
```
5. **Run the application**:
`python app.py`
6. **Visit the website**:
- Open `http://localhost:5000` in your web browser.

## 🔑Managing API Keys

It's important to keep your API keys and `SECRET_KEY` secure. Use your system's environment variables to manage these keys securely. Here is how you can set them:

- For Unix/Linux/macOS:
```
export SECRET_KEY='your_secret_key_here'
export OPENWEATHERMAP_API_KEY='your_openweathermap_api_key_here'
```
- For Windows:
```
set SECRET_KEY=your_secret_key_here
set OPENWEATHERMAP_API_KEY=your_openweathermap_api_key_here
```
Ensure these keys are never hardcoded in your source code and are not included in version control.

## 🤝Contributing

Interested in contributing? Follow these steps:

1. Fork the repo.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## 📧Contact

- Email: [artem.burov0205@gmail.com](mailto:artem.burov0205@gmail.com)
- GitHub: [buroff1](https://github.com/buroff1)
