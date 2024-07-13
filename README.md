# Bit Coin price prediction
## Introduction

Cryptocurrency markets are highly volatile, making accurate price predictions challenging. This project aims to predict Bitcoin prices using historical data and machine learning models. By leveraging models like XGBoost and LSTM, we aim to capture the patterns in the time series data for better prediction accuracy.

## Features

- Data collection and preprocessing
- Feature engineering
- Model training and evaluation
- Visualization of predictions
- Comparison of different models (e.g., XGBoost, LSTM)

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/bitcoin-price-prediction.git
cd bitcoin-price-prediction
pip install -r requirements.txt
```

## Usage

1. **Data Collection**: Ensure you have the historical Bitcoin price data. You can download data from sources like [CoinMarketCap](https://coinmarketcap.com/) or [Yahoo Finance](https://finance.yahoo.com/).

2. **Preprocessing**: Run the preprocessing script to clean and prepare the data.
   ```bash
   python preprocess.py
   ```

3. **Training**: Train the machine learning models using the prepared data.
   ```bash
   python train.py
   ```

4. **Prediction**: Use the trained models to make predictions.
   ```bash
   python predict.py
   ```

5. **Visualization**: Visualize the predictions and compare with actual prices.
   ```bash
   python visualize.py
   ```

## Model Overview

### XGBoost

XGBoost is a scalable and efficient gradient boosting framework. It provides high performance and accuracy for regression tasks, making it suitable for predicting Bitcoin prices.

### LSTM (Long Short-Term Memory)

LSTM is a type of recurrent neural network (RNN) capable of learning long-term dependencies. It's effective for time series prediction, capturing temporal patterns in Bitcoin prices.

## Results

The models' performance will be evaluated using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Visualizations will help in comparing predicted prices with actual prices over time.
