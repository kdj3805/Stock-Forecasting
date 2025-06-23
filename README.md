# 📈 Stock Forecasting with ARIMA, SARIMA, Prophet & LSTM

🌟 **Project Overview**  
This project provides a comprehensive stock market forecasting system using four different time series models.  
We trained and evaluated classical (ARIMA, SARIMA) and advanced (Prophet, LSTM) forecasting techniques to predict stock price movements.  
All outputs are visualized using clean and intuitive Matplotlib charts.

---

## 🧪 Models Implemented

- 🔢 **ARIMA** – For short-term forecasting of stationary time series  
- 🔁 **SARIMA** – For handling seasonality in stock data  
- 🔮 **Prophet** – For trend detection and flexibility with changepoints  
- 🧬 **LSTM** – For deep learning-based long-range forecasting

---

## 🛠️ Tech Stack

**Languages & Libraries**  
- Python  
- `numpy`, `pandas`  
- `matplotlib`, `seaborn`  
- `yfinance`, `statsmodels`, `pmdarima`  
- `scikit-learn`  
- `prophet`  
- `tensorflow`, `keras`

---
## 📁 Project Structure

```

stock-forecasting/
├── arima_&_sarima.py       # Combined ARIMA & SARIMA forecasting
├── prophet.py              # Prophet-based forecasting
├── LSTM.py                 # LSTM-based forecasting
└── README.md               # Project documentation

```
---
## 🎯 Model Usage Tips**
| Model   | When to Use                            | Notes                                      |
| ------- | -------------------------------------- | ------------------------------------------ |
| ARIMA   | Stable, stationary series              | Quick and interpretable                    |
| SARIMA  | Seasonality observed in data           | Use ACF/PACF or Auto ARIMA for tuning      |
| Prophet | Trend shifts, missing values, outliers | Ideal for business forecasting             |
| LSTM    | Long-range, non-linear patterns        | Requires data scaling and sequence shaping |


---

## 📊 Visual Output

Each model generates forecast plots using `matplotlib`, comparing predicted vs actual stock prices.

---

## 🧠 Learning Outcomes

* 💡 Understood differences between statistical and deep learning forecasting techniques
* 💡 Learned financial time series preprocessing and stationarity testing
* 💡 Gained experience with data visualization using Matplotlib
* 💡 Applied LSTM sequence modeling using TensorFlow/Keras
* 💡 Explored Prophet's ability to handle trend changes and missing data

---

## 👨‍💻 Project Author

This project was developed as part of a learning initiative in time series forecasting and as a part of one month internship.

---

## Contributors:
* Krupa Jantrania
* Krisha Mangukiya
* Sai Priya Reddy 

---

## 📚 References

* [Yahoo Finance API](https://www.yahoofinanceapi.com/)
* [Facebook Prophet Documentation](https://facebook.github.io/prophet/)
* [TensorFlow LSTM Guide](https://www.tensorflow.org/tutorials/structured_data/time_series)
* [Statsmodels Documentation](https://www.statsmodels.org/)
* [pmdarima Documentation](https://alkaline-ml.com/pmdarima/)
