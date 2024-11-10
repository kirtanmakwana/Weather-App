# Weather App

This is a simple weather application built using Django that allows users to get current weather data for different cities. The app fetches weather data from a public API and displays it in an easy-to-understand format.

## Features

- Search for the current weather of any city.
- Displays temperature, weather conditions, humidity, wind speed, and other details.
- User-friendly interface with a clean design.
- Error handling for invalid city names or network issues.

## Requirements

- Python 3.10
- Django 5.1.3 or later
- Requests (for making API calls)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kirtanmakwana/Weather-App.git
   cd weather-app
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your weather API key:
   - Sign up for an API key at [OpenWeather](https://openweathermap.org/) (or any other weather API provider).
   - In your Django settings, add the API key as an environment variable or directly in the code as needed.

5. Run migrations to set up the database:
   ```bash
   python manage.py migrate
   ```

6. Start the Django server:
   ```bash
   python manage.py runserver
   ```

## Usage

1. Open your web browser and go to `http://127.0.0.1:8000/`.
2. Enter a city name in the search box to view the current weather information.
3. The weather information for the city will be displayed, including temperature, weather description, humidity, and wind speed.

## Folder Structure

```
weather-app/
├── weather_app/          
├── weather_project/         
├── db.sqlite3/            
├── manage.py           
└── README.md           
```

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License.
