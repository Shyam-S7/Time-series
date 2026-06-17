Retail Sales Forecasting using ARIMA, SARIMAX, and Prophet

Project Overview

This project focuses on forecasting retail sales using time series analysis techniques. The objective is to predict future weekly sales by analyzing historical sales patterns and external factors such as holidays, temperature, fuel prices, CPI, and unemployment rates.

The project compares multiple forecasting approaches including ARIMA, SARIMAX, and Prophet to determine the most effective model for sales prediction.

---

Problem Statement

Accurate sales forecasting helps businesses:

- Manage inventory efficiently
- Reduce stock shortages and overstock situations
- Improve demand planning
- Support business decision-making

This project aims to forecast future sales based on historical retail data.

---

Dataset

The project uses the Walmart Retail Sales dataset consisting of:

Train Dataset

- Store
- Department
- Date
- Weekly Sales
- IsHoliday

Features Dataset

- Temperature
- Fuel Price
- CPI
- Unemployment
- MarkDown Features

Store Dataset

- Store Type
- Store Size

The datasets are merged to create a unified forecasting dataset.

---

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Prophet
- Scikit-learn

---

Project Workflow

1. Data Preprocessing

- Data loading
- Dataset merging
- Handling missing values
- Date conversion
- Data cleaning

2. Exploratory Data Analysis

- Sales trend visualization
- Rolling mean analysis
- Rolling standard deviation analysis

3. Stationarity Testing

- Augmented Dickey-Fuller (ADF) Test
- Differencing
- Log Transformation

4. Time Series Analysis

- ACF Plot
- PACF Plot
- Trend Analysis

5. Forecasting Models

ARIMA

AutoRegressive Integrated Moving Average model used for univariate time series forecasting.

SARIMAX

Seasonal ARIMA with exogenous variables that incorporates additional external factors affecting sales.

Prophet

Facebook Prophet model for handling seasonality, trends, and holiday effects.

6. Model Evaluation

Models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

Results

The forecasting models successfully captured sales trends and generated future sales predictions.

Key outcomes:

- Historical sales patterns were identified.
- Stationarity was achieved through transformations and differencing.
- Multiple forecasting techniques were compared.
- Future weekly sales forecasts were generated.

---

Future Improvements

- Forecast multiple stores and departments simultaneously.
- Add feature engineering techniques.
- Implement XGBoost and LightGBM forecasting models.
- Perform hyperparameter tuning.
- Deploy the model using Streamlit.
- Create an interactive dashboard using Power BI.



---

Conclusion

This project demonstrates the complete workflow of a time series forecasting solution, including data preprocessing, stationarity testing, time series analysis, model development, evaluation, and future sales prediction using ARIMA, SARIMAX, and Prophet models.
