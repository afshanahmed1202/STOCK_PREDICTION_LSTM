# STOCK_PREDICTION_LSTM
# 📈 Time Series Forecasting using LSTM (INFY)

## 👤 Author

**Md Afshan Ahmed**

---

## 📌 Overview

This project implements a **time series forecasting model using LSTM (Long Short-Term Memory)** networks to predict stock price movements of Infosys (INFY).

The model is trained on historical stock data and evaluated using proper train-test splitting to preserve temporal dependencies and avoid data leakage.

---

## 📊 Dataset

This project uses **historical stock market data for Infosys (INFY)**.

The dataset contains financial time series data that captures market trends and patterns over time, making it suitable for sequence-based deep learning models.

### 📌 Features used:

* Open
* High
* Low
* Close
* Volume

---

## 🚀 Features

* Time series forecasting using LSTM
* Sequential data modeling using sliding window approach
* Data normalization using MinMaxScaler
* Deep learning model implementation
* Evaluation using:

  * MSE (Mean Squared Error)
  * RMSE (Root Mean Squared Error)
  * MAE (Mean Absolute Error)
* Visualization of predicted vs actual values

---

## 🛠️ Tech Stack

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 🧠 Model Architecture

* **Input:** Sequence of past time steps
* **Model:** LSTM layer(s)
* **Output:** Predicted future stock price

### Flow:

Input Sequence → LSTM → Fully Connected Layer → Output Prediction

---

## ⚙️ Data Preprocessing

* Date formatting and sorting
* Handling missing values
* Scaling data using **MinMaxScaler**
* Creating sequences using time steps (sliding window method)

---

## 🔁 Train-Test Strategy

* Data split into training and testing sets
* Temporal order preserved (no random shuffling)
* Model trained on past data and tested on future data

---

## 📊 Results

* Model captures general trends in stock prices
* Predictions follow the actual curve with some deviation
* Performance depends on:

  * Data quality
  * Sequence length
  * Model tuning

---


## 📌 Important Notes

* Stock price prediction is inherently uncertain
* LSTM models capture temporal dependencies but cannot fully model sudden market volatility

---

## 🚀 Acknowledgment 
 This project was developed as part of a college assignment on time series forecasting and deep learning.


