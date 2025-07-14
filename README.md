# Stock Price Forecasting using ARIMA, XGBoost, and Prophet

This project forecasts the **VWAP (Volume Weighted Average Price)** of Bajaj Finance stock using three approaches:

- ARIMA (AutoRegressive Integrated Moving Average)
- XGBoost Regressor
- Facebook Prophet

## 📊 Dataset
- Source: Uploaded manually (NSE stock data)
- Columns used: VWAP, High, Low, Volume, Turnover,Trades

## 🔧 Methods Used
- Data Preprocessing
- Feature Engineering (rolling stats)
- Stationarity check (ADF test, ACF, PACF)
- Model Building and Evaluation (MAE, RMSE)
- 30-day forecast and comparison

## 📌 Results
| Model     | MAE    | RMSE   |
|-----------|--------|--------|
| ARIMA     | 60.15    | 80.30    |
| XGBoost   | **46.29** | **65.06** |
| Prophet   | 354.23 | 373.36 |

✅ XGBoost gave the best performance in forecasting next 30 days of VWAP prices.

## 🧠 Skills Used
- Time Series Analysis
- Machine Learning Regression
- Data Visualization
-Prophet
---

⭐ *Feel free to fork, star, or suggest improvements!*
