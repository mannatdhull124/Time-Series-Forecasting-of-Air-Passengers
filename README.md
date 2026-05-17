# Time-Series-Forecasting-of-Air-Passengers
This project focuses on forecasting air passenger trends using ARIMA and SARIMA time series models. The dataset was analyzed for trend and seasonality, followed by model training, evaluation, and future forecasting. SARIMA achieved better performance by capturing seasonal patterns effectively.
# Air Passenger Forecasting using ARIMA and SARIMA

## Overview
This project focuses on forecasting airline passenger traffic using Time Series Analysis techniques. The Air Passengers dataset was analyzed to identify trends, seasonality, and patterns over time. Initially, the ARIMA model was implemented for forecasting, but due to seasonal behavior in the dataset, the SARIMA model was later applied to improve prediction accuracy.

---

## Objectives
- Analyze historical air passenger data
- Identify trends and seasonal patterns
- Perform stationarity testing
- Build ARIMA and SARIMA forecasting models
- Compare model performances
- Predict future passenger counts

---

## Dataset Information
The dataset contains monthly airline passenger numbers.

### Features
- Month
- Passengers

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Google Colab

---

## Project Workflow

### 1. Data Preprocessing
- Imported dataset
- Converted Month column into datetime format
- Set Month as index
- Checked missing values

### 2. Exploratory Data Analysis
- Visualized trends and seasonality
- Rolling mean and standard deviation analysis

### 3. Stationarity Testing
- Applied Augmented Dickey-Fuller (ADF) Test
- Performed differencing for stationarity

### 4. ARIMA Model
- Trained ARIMA model
- Generated predictions
- Evaluated performance

### 5. SARIMA Model
- Applied SARIMA for seasonal forecasting
- Compared predictions with actual values
- Improved forecasting accuracy

### 6. Future Forecasting
- Predicted future passenger values
- Visualized future forecasts

---

## Results
- ARIMA captured overall trends but struggled with seasonality.
- SARIMA provided better forecasting performance by handling seasonal patterns effectively.
- Future forecasts showed continued growth in airline passenger traffic.

---

## Visualizations Included
- Original Time Series Plot
- Rolling Mean & Standard Deviation
- Differenced Series Plot
- ACF & PACF Plots
- Actual vs Predicted Graphs
- Future Forecast Plot
- Residual Analysis
- Model Comparison Plot

---

## Conclusion
This project demonstrates the implementation of ARIMA and SARIMA models for time series forecasting. SARIMA outperformed ARIMA due to its ability to capture both trend and seasonal patterns in airline passenger data.

---

## Author
Mannat
