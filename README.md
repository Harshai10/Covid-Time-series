# COVID-19 Time Series Prediction Benchmark

A Python-based project that implements and compares different time series prediction models for COVID-19 cases in India. The project analyzes data from January 2020 to July 2021 using various machine learning approaches.

## Models Implemented

The project compares three different time series prediction models:
1. Long Short-Term Memory (LSTM)
2. Simple Recurrent Neural Network (RNN)
3. ARMA (Autoregressive Moving Average)

## Features

- Data preprocessing and cleaning of COVID-19 time series data
- Implementation of three different prediction models
- Visualization of COVID-19 cases trends
- Performance comparison between different models
- 7-day moving average calculations
- Separate analysis for confirmed cases, deaths, and recoveries

## Dataset

The project uses the following datasets:
- `time_series_covid19_confirmed_global.csv`: Global confirmed COVID-19 cases
- `time_series_covid19_deaths_global.csv`: Global COVID-19 deaths
- `time_series_covid19_recovered_global.csv`: Global COVID-19 recoveries

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

## Usage

1. Ensure all required dependencies are installed
2. Place the CSV data files in the same directory as the script
3. Run the script:
   ```
   python covid_time_series_benchmark.py
   ```

## Project Structure

- `covid_time_series_benchmark.py`: Main Python script containing the implementation
- `stationarity vs non stationarity.png`: Visualization of time series stationarity
- Data files:
  - `time_series_covid19_confirmed_global.csv`
  - `time_series_covid19_deaths_global.csv`
  - `time_series_covid19_recovered_global.csv`

## Features of the Implementation

- Data preprocessing including normalization and time series transformation
- Time series prediction with a 7-day window
- Train-test split (80-20)
- MinMax scaling for feature normalization
- Visualization of predictions and actual values
- Model performance comparison

## Author

Harsha Vardhan J

## References

- [COVID-19 Case Prediction with LSTM (Kaggle)](https://www.kaggle.com/code/greysky/covid-19-case-prediction-with-lstm/notebook)
- [Complete Guide to SARIMAX in Python](https://analyticsindiamag.com/complete-guide-to-sarimax-in-python-for-time-series-modeling/)
