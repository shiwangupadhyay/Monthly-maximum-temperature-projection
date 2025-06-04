# 🌡️ Monthly Maximum Temperature Forecast

This project forecasts the **monthly maximum temperatures** in **Madrid, Spain** for the year 2024 using historical weather data and time series modeling via SARIMAX. It uses Python, the Meteostat API, and Statsmodels for seasonal decomposition and forecasting.

---

## 📌 Objectives

- Retrieve historical max temperature data for Madrid
- Visualize long-term trends and seasonal patterns
- Decompose the time series into trend, seasonality, and residuals
- Verify stationarity with statistical tests
- Build and tune a SARIMAX model
- Forecast monthly max temperature for 2024

---

## 📊 Data Source

- **API**: [Meteostat](https://dev.meteostat.net/)
- **Location**: Madrid, Spain (Latitude: 40.4168, Longitude: -3.7038)
- **Elevation**: 657 meters
- **Frequency**: Monthly
- **Variable**: `tmax` – Maximum monthly temperature

---

## 🧰 Technologies Used

- Python 3.10+
- pandas
- numpy
- matplotlib
- statsmodels
- meteostat

---

## 🧪 Workflow Summary

### 1. Data Collection
### 2. Visualization
### 3. Seasonal Decomposition
### 4. Stationarity Check (ADF Test)
### 5. ACF and PACF Plots
### 6. Train-Test Split
### 7. SARIMAX Hyperparameter Tuning
### 8. Fit SARIMAX Model
### 9. Forecast for 2024
### 10. Visualization of Forecast

📈 Results Summary
- The SARIMAX model successfully captured seasonal patterns in the data.
- Forecast shows expected monthly max temperatures with confidence bounds.
- Residuals and ACF/PACF support model adequacy.

🧪 Key Learnings
- Time series stationarity and seasonality are critical for modeling
- Grid search over SARIMAX hyperparameters improves accuracy (via AIC)
- Decomposition and autocorrelation tools are essential diagnostics

