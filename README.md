# Time Series Forecasting: SARIMAX vs LightGBM vs XGBoost

This project compares three different machine learning models — SARIMAX, LightGBM, and XGBoost — for time series forecasting using real-world retail data from Walmart. The primary objective is to evaluate and analyze the performance of these models in predicting weekly sales for a specific store.

---

## 📊 Dataset

The dataset used is from Walmart's historical sales records. It includes:
- `Store`: Store ID
- `Date`: Weekly sales date
- `Weekly_Sales`: Target variable for forecasting

---

## 🔍 Objective

To forecast weekly retail sales using three different models and compare their performance based on:
- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)
- Visual accuracy (Actual vs Predicted plots)

---

## 🧠 Models Compared

| Model     | Description |
|-----------|-------------|
| **SARIMAX** | A classical statistical approach using seasonal ARIMA with exogenous factors |
| **LightGBM** | A fast, histogram-based gradient boosting model that works well with structured time series features |
| **XGBoost** | A regularized gradient boosting model known for high performance and speed |

---

## ⚙️ Features Engineered

- Lag features (1, 2, 3, 4, 52 weeks)
- Date-based features (month, year, weekofyear, day)
- Outlier removal using 3-sigma method
- Weekly resampling and interpolation for consistent frequency

---

## 📈 Evaluation Metrics

Each model is evaluated using:
- **RMSE** – Root Mean Squared Error
- **MAE** – Mean Absolute Error

A comparison table is provided in the notebook for side-by-side evaluation.

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/retail-forecast-comparison.git
