# Stock Predictor

This project provides a **Stock Predictor** for analyzing A stock's historical performance and predicting future prices. It leverages Python for data preprocessing, TensorFlow's LSTM (Long Short-Term Memory) models for time-series forecasting, and Matplotlib for data visualization. The project demonstrates end-to-end data handling, model training, and prediction capabilities.


---

## Features

- **Data Preprocessing**: Cleans and organizes stock data for modeling.
- **Predictive Modeling**: Uses LSTM networks to predict future Tesla stock prices.
- **Visualization**: Employs Matplotlib to display historical trends, model performance, and predictions.
- **Future Price Prediction**: Forecasts the Stocks closing stock prices based on historical trends.
-                     TSLA                             GOOG                              MSFT
<img src="https://github.com/user-attachments/assets/ec022f06-bc1e-47ee-94ec-bc890df54967" width="300">
<img src="https://github.com/user-attachments/assets/c65772b5-cec1-4653-adca-4396bca0c858" width="300">
<img src="https://github.com/user-attachments/assets/dd351163-045b-44c6-ac13-1d1d3f71236e" width="300">


---

## How It Works

### 1. Data Preprocessing

The predictor starts by importing and processing historical stock data from a CSV file. It ensures the data is properly scaled and reshaped for the LSTM model. This involves:
- Filtering columns like `date` and `close`.
- Converting dates to a datetime format.
- Normalizing the stock prices for efficient model training.

### 2. Predictive Modeling with TensorFlow LSTM

The project utilizes TensorFlow's LSTM, a powerful neural network architecture for sequential data. Key steps include:
- **Data Splitting**: Divides the dataset into training and testing sets.
- **Feature Scaling**: Normalizes data to improve model performance.
- **Model Architecture**: Defines an LSTM model with layers optimized for time-series forecasting.
- **Training**: Fits the model on historical stock data to capture temporal patterns.
- **Prediction**: Outputs future Tesla stock prices.

### 3. Visualization with Matplotlib

Matplotlib is used to:
- Plot historical stock prices to identify trends.
- Compare actual vs. predicted prices to evaluate model performance.
- Display future price predictions for Tesla's stock.
