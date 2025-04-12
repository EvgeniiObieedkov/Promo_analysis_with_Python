# Promo_analysis_with_Python

---

# 📈 Promo Campaign Effectiveness Analysis

This project analyzes the effectiveness of a 92-day promotional campaign (Jan 1 – Apr 2, 2023) aimed at increasing affiliate-driven revenue in a travel content monetization platform.

## 🔍 Objective

To determine whether the promo campaign led to a significant increase in **total Revenue** (Affiliate Profit + Company Profit) by comparing actual revenue against a forecast generated using historical data.

## 📦 Contents

- `Revenue_historical_data.csv` — Daily revenue data before the promo campaign.
- `Revenue_promo_data.csv` — Actual revenue data during the promo campaign.
- Prophet model for time series forecasting.
- Outlier smoothing using IQR and rolling mean.
- ADF test for stationarity check.
- R² score for model performance evaluation.
- Final interpretation of promo campaign impact.

## 🛠 Methods

- Time series forecasting using Facebook Prophet.
- Outlier detection and correction (IQR method).
- Forecast validation with historical data split.
- Visualizations with Plotly.

## ✅ Conclusion

The model compares actual promo revenue with the upper bound of the Prophet forecast. If actual revenue **exceeds the forecast**, the campaign is considered **successful**.

---
