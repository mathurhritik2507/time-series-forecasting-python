# Time Series Forecasting Using Python

## Overview

This project focuses on analyzing monthly time series data and building forecasting models to predict future trends. The project uses Python-based forecasting techniques including SARIMA and Prophet, along with trend analysis, seasonality evaluation, and model performance comparison.

## Objective

The main objective of this project is to understand historical data patterns, identify trends and seasonality, and generate future forecasts using statistical and machine learning-based time series models.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- SARIMA
- Prophet
- Jupyter Notebook

## Repository Structure

```text
time-series-forecasting-python/
├── README.md
├── time_series_forecasting.ipynb
├── requirements.txt
├── data/
│   └── dataset.csv
├── images/
│   ├── trend_plot.png
│   ├── forecast_plot.png
│   └── model_evaluation.png
└── report/
    └── project_summary.pdf
```

## Dataset

The dataset contains monthly revenue values from January 2019 to December 2024. It is structured with two columns:

- `date`: monthly date value
- `revenue`: numeric revenue value used for forecasting

## Methodology

1. Loaded and cleaned the monthly dataset.
2. Converted the date column into proper time series format.
3. Performed exploratory data analysis to understand trends and seasonality.
4. Applied SARIMA model for statistical forecasting.
5. Added Prophet workflow as an optional forecasting approach.
6. Compared forecasted values with actual test data using evaluation metrics.
7. Visualized trend, forecast output, and model evaluation results.

## Results

The project generated future forecasts and visualized predicted trends. The evaluation summary from the included baseline model is:

- MAE: `1,869.86`
- RMSE: `2,316.58`
- MAPE: `3.47%`

## Key Learnings

- Time series preprocessing and date indexing
- Trend and seasonality analysis
- SARIMA forecasting workflow
- Prophet forecasting workflow
- Forecast visualization and model comparison
- Understanding limitations in real-world time series data

## Future Improvements

- Add more historical data
- Improve feature engineering
- Compare ARIMA, SARIMA, Prophet, LSTM, and XGBoost
- Deploy the model using Streamlit or Flask
