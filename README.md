# 🛒 Demand Forecasting for Retail Sales

This project applies **classical statistical models** and **modern machine learning approaches** to forecast weekly sales of a retail store.  

## 📊 Models Implemented
- **ARIMA** → Captures short-term linear patterns
- **SARIMA** → Extends ARIMA with seasonality
- **LSTM (Deep Learning)** → Learns complex, non-linear patterns
- **Facebook Prophet** → Captures trend, seasonality, and holidays (business-friendly)

## 🚀 Workflow
1. Data Cleaning & Preprocessing
2. Stationarity Check (ADF Test)
3. ARIMA & SARIMA modeling
4. LSTM sequence modeling
5. Prophet forecasting
6. Model comparison (RMSE, MAE)

## 📈 Results
- ARIMA: 
<img width="1409" height="591" alt="image" src="https://github.com/user-attachments/assets/770395c6-e9a5-4e6c-b295-519070b0ea67" />

- SARIMA: 
<img width="1314" height="568" alt="image" src="https://github.com/user-attachments/assets/cdf0d53a-e669-4ead-b663-32dada9acb83" />

- LSTM:
<img width="1321" height="564" alt="image" src="https://github.com/user-attachments/assets/177606c3-0d46-4af7-aa24-84f379694cef" />

- Prophet: RMSE = ...
<img width="1320" height="709" alt="image" src="https://github.com/user-attachments/assets/6150a98f-a7bc-4ac6-a55f-58ef2c518647" />


## 🛠 Tech Stack
- Python, Pandas, Numpy
- Statsmodels, Prophet
- TensorFlow/Keras
- Matplotlib, Seaborn

## 🔗 How to Run
```bash
git clone https://github.com/yourusername/demand-forecasting-sales.git
cd demand-forecasting-sales
pip install -r requirements.txt
