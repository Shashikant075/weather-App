
# Weather-App


Weather application built using the Django web framework and powered by the WeatherOpenAPI. This project provides a user-friendly interface to access up-to-date weather information for locations around the world.


## Features

- Real-Time Weather Data:  The application utilizes the WeatherOpenAPI to fetch real-time weather data, ensuring that users receive accurate and current information.
- Location-Based Weather:   Users can search for weather information by specifying a location, such as a city or coordinates. The application provides detailed weather forecasts, including temperature, humidity, wind speed, and more.
- User-Friendly Interface:  The user interface is designed to be intuitive and visually appealing, making it easy for users to interact with and obtain weather information quickly.



## Screenshots


![Screenshot 2023-09-30 184812](https://github.com/Shashikanttt/weather-App/assets/101270238/845158b3-1c93-4ca2-b1d4-7159b857ff85)


## Run Locally


To set up the Employee Management System, follow these steps:

1. Clone the repository to your local machine.



```bash
  https://github.com/Shashikanttt/weather-App.git
```

Go to the project directory

```bash
  cd weather
```

Create Virtual Environment

```bash
  py -m venv venv   #install virtual enviroment
  venv\scripts\activate   #activate virtual enviroment venv
```
Install

```bash
  pip install -r requirements.txt #install required packages
  py manage.py migrate # run first migration
```

Start the server

```bash
  python manage.py runserver # run the server
```


## Usage


To use the Weather App, follow these steps:

Access the system via the provided URL (e.g., http://127.0.0.1:8000/ ).



```bash
    http://127.0.0.1:8000/

```
Search  by location as needed.






