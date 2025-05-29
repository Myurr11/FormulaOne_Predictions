# F1 Race Time Prediction

![F1](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Formula_1_logo.svg/1200px-Formula_1_logo.svg.png)

## Project Overview

This project is a **Formula 1 race lap time and race result prediction model** built using machine learning techniques. It leverages the [FastF1](https://theoehrly.github.io/Fast-F1/) Python library to extract live and historical F1 telemetry data, combined with weather information and driver/team performance metrics.

The goal is to analyze various race and qualifying parameters, then predict race lap times and ultimately forecast race outcomes such as the winner and podium finishes.

---

## Features

- Loads and processes telemetry data from FastF1 for specific F1 race sessions.
- Integrates qualifying times, sector times, and race pace data.
- Uses live weather data from OpenWeatherMap API to factor in weather conditions.
- Incorporates team performance and historical driver position changes.
- Trains a Gradient Boosting Regressor ML model to predict lap times.
- Visualizes feature importances and relationships between variables.
- Outputs predicted race winner and top 3 podium finishers.

---

## Development Status
🚧 **Under Development** 🚧

This project is built for learning machine learning and F1 data analytics out of pure passion. As the F1 season progresses, I will add prediction files for upcoming races, refine the model, and enhance features for better accuracy.

---

## Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/f1-race-time-prediction.git
   cd f1-race-time-prediction
2. Install dependencies (preferably in a virtual environment):

   ```bash
   pip install fastf1 pandas numpy scikit-learn matplotlib requests
3. Get an API key from OpenWeatherMap and add it to the code.
