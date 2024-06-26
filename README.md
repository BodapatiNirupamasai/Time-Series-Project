# Time-Series-Project

This project focuses on conducting an in-depth analysis of a Lumber Price time series variable, starting with exploratory data analysis and time series decomposition. The data source and generating process are identified, followed by the calculation of summary statistics and visualizations to understand the behavior and distribution of the time series. 
1. Moving averages are visualized, and seasonality is assessed through time series decomposition. The data is then split into training and test sets for further analysis.
2. In the ARIMA modeling section, the variance and mean stationarity of the data are assessed using statistical tests like KPSS.
3. Transformations are applied to induce stationarity or remove seasonality, and ACF/PACF plots guide the selection of an appropriate ARIMA model based on AIC/BIC. Model residuals are analyzed for autocorrelation.
4. The Meta Prophet Model section involves building a Prophet model by assessing trend, seasonality, changepoints, and hyperparameters. Seasonality at different intervals is identified and visualized.
5. The final section compares the performance of various models including ARIMA, Prophet, and naive models through rolling window cross-validation on the training set. The best model is selected based on forecast performance, evaluated on the test set. The chosen model is then refit to all data for future forecasting.
6. This project aims to provide a comprehensive analysis of time series data using ARIMA modeling, Prophet modeling, and model comparison techniques to enhance forecasting accuracy and decision-making processes.
