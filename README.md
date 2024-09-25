# Amazon Stock Price Prediction using LSTM

## Overview

This repository contains a deep learning project that predicts **Amazon stock prices** using a Long Short-Term Memory (LSTM) network. LSTMs are well-suited for time series forecasting, as they can capture long-term dependencies in data, making them ideal for financial prediction tasks.

The project achieved a **final test loss of 0.0031**, indicating the model's ability to accurately predict stock prices based on historical data.

## Dataset

- The dataset consists of historical stock price data for Amazon, including features like **Open**, **Close**, **High**, **Low**, and **Volume**.
- The primary feature used for prediction is the **Closing Price** of the stock.

## Model Architecture

- The model is built using an LSTM architecture.
- **Input size**: 1 (Closing price for each timestep).
- **Hidden layers**: LSTM with a hidden size of 4.
- **Fully connected layer**: A linear layer to map the LSTM output to the predicted stock price.
- The LSTM model was trained using **Mean Squared Error (MSE)** as the loss function.

## Results

- The model achieved a **final test loss of 0.0031**.
- The performance indicates that the model is effective at capturing the underlying patterns in Amazon stock price data and can be used for predictive tasks.
