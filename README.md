# 📈 Retail Sales Forecasting using ARIMA, SARIMAX & Prophet

## 📌 Overview

This project focuses on forecasting retail sales using classical time series forecasting techniques. Historical sales data along with external factors such as holidays, temperature, fuel prices, CPI, and unemployment are analyzed to predict future weekly sales.

The project compares multiple forecasting models:

- ARIMA
- SARIMAX
- Prophet

---

## 🎯 Objectives

- Analyze historical retail sales trends
- Perform time series preprocessing and stationarity testing
- Build forecasting models
- Compare model performance
- Generate future sales predictions

---

## 📂 Dataset

The project uses the Walmart Retail Sales Dataset.

### Train Data
| Column | Description |
|----------|-------------|
| Store | Store ID |
| Dept | Department ID |
| Date | Sales Date |
| Weekly_Sales | Weekly Sales |
| IsHoliday | Holiday Indicator |

### Features Data
- Temperature
- Fuel Price
- CPI
- Unemployment
- MarkDown Features

### Store Data
- Store Type
- Store Size

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Prophet
- Scikit-Learn

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing
- Dataset merging
- Missing value handling
- Date conversion
- Data cleaning

### 2️⃣ Exploratory Data Analysis
- Sales trend visualization
- Rolling mean analysis
- Rolling standard deviation analysis

### 3️⃣ Stationarity Testing
- ADF Test
- Differencing
- Log Transformation

### 4️⃣ Time Series Analysis
- ACF Plot
- PACF Plot

### 5️⃣ Forecasting Models

#### ARIMA
AutoRegressive Integrated Moving Average model for time series forecasting.

#### SARIMAX
Seasonal ARIMA with exogenous variables.

#### Prophet
Forecasting model developed by Meta for trend and seasonality analysis.

### 6️⃣ Model Evaluation

Metrics used:

- MAE
- MSE
- RMSE

---

## 📊 Results

✔ Successfully analyzed sales trends

✔ Achieved stationarity through transformations

✔ Built and compared multiple forecasting models

✔ Generated future weekly sales forecasts


---

## 🚀 Future Improvements

- Forecast multiple stores and departments
- Add feature engineering
- Implement XGBoost forecasting
- Implement LightGBM forecasting
- Hyperparameter tuning
- Deploy using Streamlit
- Create Power BI Dashboard



---

## 👨‍💻 Author

Shyam

