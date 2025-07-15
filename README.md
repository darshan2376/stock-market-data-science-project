# stock-market-data-science-project
# 📈 LSTM Price Forecast – NIFTY Stock Market

This project uses LSTM (Long Short-Term Memory) deep learning model to predict future closing prices of the NIFTY index.

---

## 📊 Objective

Forecast next 30 days of NIFTY closing prices using historical data (2010–2023) with LSTM model.

---

## 📁 Dataset

- Source: [Yahoo Finance](https://finance.yahoo.com/)
- Ticker: `^NSEI` (NIFTY Index)
- Columns used: `Date`, `Close`

---

## 🧠 Tools & Techniques

- Python, Pandas, NumPy
- TensorFlow / Keras (LSTM model)
- MinMaxScaler
- Matplotlib for visualizations

---

## 🔄 Workflow

1. Load and scale data
2. Create time series dataset
3. Train LSTM model
4. Predict and visualize future values

---

## 📈 Results

- LSTM predicted trend matches closely with actual values for the test set
- Shows reasonable accuracy for short-term stock price movement

![Prediction Plot](results/lstm_prediction.png)

---

## 🛠️ How to Run

```bash
pip install -r requirements.txt
python lstm_model.py  # if you convert code into script
