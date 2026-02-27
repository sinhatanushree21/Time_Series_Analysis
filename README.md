# Time_Series_Analysis
 Time Series Analysis: Netflix Stock Price Prediction

 This project applies time series analysis techniques to predict Netflix stock prices. The workflow demonstrates how statistical modeling can be used to uncover structure in financial data and generate forecasts.
 # Methodology
- Stationarity Testing
- Applied Augmented Dickey-Fuller (ADF) test to check if the series is stationary.
- Differencing performed when necessary to stabilize mean and variance.
- Decomposition
- Separated the series into trend, seasonality, and residuals to better understand underlying patterns.
- Modeling
- Implemented Autoregressive (AR) and Moving Average (MA) models.
- Compared models using Akaike Information Criterion (AIC) to select the best fit.
- Forecasting
- Generated predictions for Netflix stock prices using the chosen model.
- Evaluated performance with visual plots and error metrics.

  
# Tools & Libraries
- Python (NumPy, Pandas, Matplotlib, Statsmodels)
- Jupyter Notebook for reproducible analysis

  
# Key Insights
- Stationarity is crucial for reliable forecasting.
- Decomposition reveals hidden seasonal and trend components.
- AIC comparison provides a principled way to select between AR and MA models.
- The final model captures short-term dependencies in Netflix stock prices effectively.


