# Walmart Sales Forecasting Model

## 📌 Overview
A time series forecasting solution predicting Walmart's weekly sales using **SARIMA** and **Facebook Prophet** to optimize inventory management and cash flow planning.

## 🚀 Features
- **Data Preprocessing**: Handles missing values, outliers, and date formatting
- **Feature Engineering**: Lag features, rolling statistics, holiday impact analysis
- **Model Training**: SARIMA (univariate) and Prophet (multivariate with regressors)
- **Evaluation**: MAE, RMSE, MAPE metrics comparison

## 📊 Results
| Model | MAE | RMSE | MAPE |
|-------|-----|------|------|
| SARIMA | 815,781 | 1,004,033 | 69.6% |
| Prophet | **448,627** | **522,839** | 78.5% |

---
