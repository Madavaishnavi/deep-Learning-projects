# Seattle Weather Time Series Forecasting using RNN

This project forecasts temperature trends using historical weather data from Seattle. The model is built using LSTM layers and trained on several years of temperature readings.

## Project Description

- **Objective:** Predict the average daily temperature using historical time series data
- **Model:** Stacked LSTM-based Recurrent Neural Network
- **Data Source:** [Kaggle Seattle Weather Dataset](https://www.kaggle.com/datasets/ananthr1/weather-seattle)

## Features

- Time series preprocessing (datetime parsing, missing value handling, scaling)
- Visualization of temperature trends over time
- Creation of training sequences using sliding windows
- LSTM model with early stopping and dropout
- Evaluation using RMSE and visual forecasts

## Results

- Validation RMSE: ~2.3°C
- Forecast plot clearly shows learned seasonality and short-term trend
- Captures rising/falling temperature patterns effectively


## Libraries

- TensorFlow / Keras
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

---

## How to Run

1. Clone the repository
2. Navigate to `Seattle-weather-RNN-Analysis/`
3. Open and run `Analyzing_Seattle_weather.ipynb` in Jupyter


