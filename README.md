# 📊 Forecasting Indonesia Tax Revenue (Time Series Analysis)

## Overview

This project develops a data-driven forecasting model to estimate Indonesia’s tax revenue as a percentage of GDP using time series analysis and macroeconomic indicators.

The model evaluates the historical relationship between tax revenue and key macroeconomic variables, including GDP growth, inflation, and unemployment, to identify structural patterns influencing fiscal performance.

The objective is to produce a statistically robust model capable of projecting tax revenue trends for the next five years.

---

## Analytical Framework

The project follows a structured analytical workflow:

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Stationarity Testing & Transformation
5. Time Series Modeling (ARIMA / SARIMAX)
6. Model Diagnostics
7. Forecast Evaluation

---

## Methodology

* Time Series Modeling: ARIMA & SARIMAX
* Exogenous Variables:

  * GDP Growth
  * Inflation
  * Unemployment
* Statistical Tests:

  * Ljung–Box Test (autocorrelation)
  * Jarque–Bera Test (normality)

---

## Key Findings

### Historical Insights

* Tax revenue peaked at ~21.4% of GDP in 2012
* Decline observed until 2021
* Recovery trend begins post-2022
* No strong seasonality, but moderate fluctuations

### Macroeconomic Relationships

* Tax revenue is sensitive to macroeconomic conditions
* Strong linkage with labor market indicators
* Macro variables significantly improve model performance

---

## Model Performance

* MAPE: 8.93%
* MAE: 1.54
* RMSE: 1.63

Residual diagnostics indicate:

* No significant autocorrelation
* Approximately normal distribution

---

## Forecast Results

* Forecast horizon: 2026–2030
* Projected increase from **18.3% to 22.9% of GDP**

The model suggests a gradual strengthening of Indonesia’s fiscal capacity, assuming stable macroeconomic conditions.

---

## Files

* `notebook.ipynb` → Main analysis (Google Colab)
* `report.pdf` → Full analytical report
* `dataset.csv` → Input data (if included)

---

## How to Run

1. Open the notebook:
   https://colab.research.google.com/drive/1YqjPMrx8AWoVuBgPbfP2FGp-zIsKSbig

2. Run all cells sequentially

---

## Output

* Forecast visualization
* Model evaluation metrics
* Policy-relevant insights

---

## Author

Sabrina Zada
Data Analyst | Tax Analyst Intern

---

## Notes

This model is based on historical macroeconomic patterns and statistical assumptions. Forecast results should be interpreted as indicative projections rather than exact predictions.
