# Time-Series-Analysis-on-Web-Scrapped-Weather-Data
Objective: To forecast the average temperature of the day, based on data collected using Beautiful soup and Requests.\
Methodology & Results: 
1. Augmented Dickey-Fuller test and Rolling statistics are used for stationarity check in data. 
2. Parameters for ARIMA were estimated using PACF(p), ACF(q) plots.
3. Stationarity is achieved by log transform and differencing(d).
4. ARIMA(6,1,4) forecasted with Min AIC and MAPE:3.1%, SARIMA with 3.4%, and the Prophet model with 22%.
