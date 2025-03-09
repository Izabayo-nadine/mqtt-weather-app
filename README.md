# MQTT Weather Station (MQTT + SQLite)

## Overview

This project demonstrates how to use MQTT for real-time data transmission and SQLite for data storage. It collects weather data, specifically temperature and humidity, from MQTT topics and stores it in an SQLite database. The data is then visualized in real-time on a web interface using Chart.js. The app fetches the data every 30 seconds and updates the chart accordingly.

## Features

- Real-time weather data visualization using **Chart.js**.
- Data is fetched from **MQTT** topics and stored in **SQLite**.
- Displays two datasets: Temperature (°C) and Humidity (%).
- Fetches and updates weather data every 30 seconds.

## Technologies Used

- **MQTT**: Lightweight messaging protocol for real-time data transfer.
- **SQLite**: Relational database for storing weather data.
- **Chart.js**: JavaScript library for creating interactive charts.
- **Node.js**: JavaScript runtime used for the backend server.
- **Express.js**: Web framework for handling HTTP requests.

## Setup Instructions

Follow the steps below to set up the project locally:

### 1. Clone the Repository

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/yourusername/mqtt-weather-app.git
