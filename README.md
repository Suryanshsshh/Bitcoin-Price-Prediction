# 📈 Bitcoin Price Prediction using LSTM

Welcome to the **Bitcoin Price Prediction** project! 🚀  
In this notebook, we use **Python** and **Machine Learning (LSTM Neural Network)** to predict Bitcoin prices based on historical data. This project is a fascinating dive into time series forecasting, deep learning, and data visualization — all in one place.

---

## 🧠 Project Objective

To build an LSTM-based deep learning model that predicts the closing price of Bitcoin by analyzing historical trends. This can serve as a reference for understanding sequential modeling for financial data.

---

## 🧰 Technologies & Libraries Used

- Python 🐍
- NumPy & Pandas
- Matplotlib & Seaborn 📊
- TensorFlow / Keras 🧠
- Scikit-learn
- pandas_datareader for fetching stock data

---

## 📊 Data Source

We used **pandas_datareader** to fetch real-time Bitcoin data from Yahoo Finance, focusing on the **daily closing prices** as our main prediction target.

---

## 📌 Workflow Overview

1. **Data Collection**  
   Pulled historical BTC data using `pandas_datareader`.

2. **Data Preprocessing**  
   - Filtered only the `Close` price.
   - Normalized data using `MinMaxScaler`.
   - Structured data into sequences of 60 days for LSTM input.

3. **Model Building**  
   - Two stacked LSTM layers.
   - Two Dense layers.
   - Compiled with `adam` optimizer and `mean_squared_error` loss.

4. **Training**  
   Trained on ~2080 time windows of data.

5. **Prediction & Visualization**  
   - Compared predicted vs actual prices.
   - Visualized trends using `matplotlib`.

---

## 💡 Key Learnings

- Hands-on understanding of LSTM for Time Series Forecasting

- Data scaling & reshaping for sequential models

- Model evaluation using visual insights

## 📂 How to Run- 

1. **Clone this repository:**
   git clone https://github.com/yourusername/bitcoin-price-prediction.git
   cd bitcoin-price-prediction

2. **Run the notebook:**
   jupyter notebook Bitcoin_Price_Prediction.ipynb

  
 

plt.legend()
plt.show()
