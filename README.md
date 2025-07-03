# 📈 Forecasting Under Political Shocks: ARIMA, LSTM, and Prophet

A comparative time series forecasting project investigating how ARIMA, LSTM, and Prophet perform under real-world volatility and structural breaks, using the 2025 U.S. tariff shock as a case study.

---

## 🧠 Project Goal

- Evaluate the robustness and accuracy of ARIMA, Prophet, and LSTM models when exposed to both stable and politically disrupted financial markets.

---

## 📊 Data & Use Case

- Financial instruments:
  - **S&P 500 Index**
  - **Tesla Inc. stock**
- Focus event: **2025 Trump tariff announcement**
- Forecasting periods include both:
  - **Pre-shock (stable)**
  - **Post-shock (volatile)**

---

## 🛠️ Models Used

- **ARIMA** – Classical statistical model assuming stationarity.
- **Prophet** – Trend-seasonality-based model with change-point detection.
- **LSTM** – Deep learning model for capturing nonlinear temporal dependencies.

---

## 📈 Evaluation Metrics

- **RMSE** – Root Mean Squared Error  
- **MAE** – Mean Absolute Error  
- **MAPE** – Mean Absolute Percentage Error  
- **Z-score residual analysis** – For detecting instability and anomalous predictions

---

## 💡 Key Findings

- **LSTM** outperformed ARIMA and Prophet in volatile regimes due to better adaptability to nonlinear patterns.
- **ARIMA** and **Prophet** performed acceptably under stable conditions but failed to react to structural breaks.
- All models exhibited reduced forecasting reliability after the political shock.

---

## 🔍 Next Steps & Research Outlook

- Develop **hybrid forecasting models** combining statistical and deep learning methods.
- Integrate **exogenous variables** (e.g., macroeconomic indicators, sentiment data).
- Investigate modern architectures:
  - [Informer](https://arxiv.org/abs/2012.07436)
  - [Autoformer](https://arxiv.org/abs/2106.13008)
  - [TFT](https://arxiv.org/abs/1912.09363)
  - [N-BEATS](https://arxiv.org/abs/1905.10437)
