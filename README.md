📈 Stock Price Prediction using RNN and LSTM
📌 Project Overview

This project implements Stock Price Prediction using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models.

The goal of this project is to analyze historical stock price data and predict future stock closing prices using deep learning techniques.

The project compares the performance of:

🔹 Simple RNN

🔹 LSTM

LSTM is expected to perform better because it handles long-term dependencies more effectively.

🧠 Technologies Used

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Scikit-learn

yFinance

📊 Dataset

Stock market data is fetched using the yfinance API.

Example stock used:

Apple Inc. (AAPL)

You can change the stock symbol to:

TSLA (Tesla)

GOOG (Google)

MSFT (Microsoft)

Any other available stock

⚙️ Project Workflow

Data Collection using yFinance

Data Preprocessing

Selecting Close prices

Normalization using MinMaxScaler

Creating time-series sequences (60 days window)

Train-Test Split (80% - 20%)

Building RNN Model

Building LSTM Model

Model Training

Prediction on test data

Performance Evaluation using RMSE

Visualization of results

📈 Model Architecture
🔹 RNN Model

2 SimpleRNN layers (50 units each)

1 Dense output layer

Optimizer: Adam

Loss Function: Mean Squared Error

🔹 LSTM Model

2 LSTM layers (50 units each)

1 Dense output layer

Optimizer: Adam

Loss Function: Mean Squared Error

📉 Evaluation Metric

The models are evaluated using:

RMSE (Root Mean Squared Error)

Lower RMSE indicates better prediction performance.

📊 Output

Graph comparing:

Actual Stock Price

RNN Predictions

LSTM Predictions

RMSE values printed in terminal

Next day stock price prediction
