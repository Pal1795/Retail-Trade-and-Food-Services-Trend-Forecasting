# Retail-Trade-and-Food-Services-Trend-Forecasting

**Project Overview**

This project aims to leverage advanced time series analysis techniques to create a comprehensive framework for predicting trends in retail trade and food services across the United States. By employing various forecasting methods learned through coursework, we aim to build reliable models that can accurately predict future trends within these industries. The goal is to provide precise forecasts that will assist businesses, policymakers, and stakeholders in making informed decisions and strategic plans for the retail sector.

**Key Findings**
 - Trend and Seasonality: The dataset reveals an upward trend with seasonal variations, characterized by lower sales at the beginning of the year and a peak toward the year-end.

 - Autocorrelation: The data exhibits strong autocorrelation, with all 12 lags showing statistically significant autocorrelation coefficients.

**Methods**

We applied a combination of the following time series forecasting models:

1. Regression-Based Models
 - We utilized both Linear and Quadratic Regression Models to capture the underlying trends.

 - A Two-Level Forecasting method was employed to improve the regression models.

 - We incorporated a Trailing Moving Average for residuals to enhance the model's accuracy.

2. Advanced Exponential Smoothing Models
 - We implemented the Holt-Winters method to account for seasonality and trend in the data.

 - Various variations of the model were tested to optimize performance.

3. ARIMA Models
 - Auto ARIMA was used for time series forecasting, which automatically selects the best ARIMA model based on the data.

**Model Evaluation**

Models were evaluated using the following accuracy metrics:

 - Root Mean Squared Error (RMSE)

- Mean Absolute Percentage Error (MAPE)

**Best Performing Model**

Based on evaluation metrics, the Auto ARIMA model emerged as the most effective model for forecasting retail sales trends in the trade and food services sectors.

**Conclusion**

The selected model is Auto ARIMA the optimal choice for forecasting. Following closely are Linear Trend and Seasonality with a Trailing Moving Average, and Quadratic Trend and Seasonality with a Trailing Moving Average. However, the Holt Winter Model is not considered among the top choices due to its limitation in handling seasonal components. As previously mentioned, it's imperative to re-evaluate the chosen model semi-annually to maintain accuracy in forecasting for upcoming fiscal periods.

