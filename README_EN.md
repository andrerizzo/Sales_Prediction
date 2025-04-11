# 📈 Sales Forecasting with Time Series

## 🔍 Introduction
This project aims to analyze and forecast sales volume over time based on historical data. Sales forecasting is essential for strategic decision-making in areas such as marketing, logistics, finance, and production.

The study is divided into stages to structure a complete forecasting pipeline, including exploratory data analysis, data preprocessing, and application of time series models.

---

## 🎯 Objectives
- Analyze temporal patterns in sales (trend, seasonality, outliers)
- Build univariate forecasting models
- Prepare the project for further development with multivariate or machine learning models

---

## 🧠 Project Stages

### ✅ Part 1 — Exploratory Data Analysis
- Data inspection
- Visualization of trend and seasonality
- Stationarity checks

### ✅ Part 2 — Preprocessing
- Date conversion and chronological ordering
- Handling missing values
- Aggregation by time frequency (weekly/monthly)

### ✅ Part 3 — Univariate Models
- Application of classic time series models (e.g., moving average, decomposition, ARIMA)
- Evaluation of forecasting performance using metrics such as RMSE and MAE

---

## 📦 Libraries Used
- pandas
- matplotlib / seaborn
- statsmodels
- numpy
- scikit-learn (optional)

---

## 📊 Results
The project demonstrated the feasibility of forecasting sales volumes based on historical patterns. Even simple univariate models showed promising performance, especially for series with clear trends and marked seasonality.

### Comparison of Time Series Model Performance

| Modelo          | MAE         | MSE             | RMSE        | MAPE (%) |
|----------------|-------------|------------------|-------------|-----------|
| **Holt-Winters**   | **1.158.055,01** | **2.509.331.616.379,43** | **1.584.087,00** | **2,49** |
| SES            | 2.236.854,38 | 6.970.201.281.512,38 | 2.640.113,88 | 4,89      |
| ARIMA (5,1,5)  | 1.776.843,04 | 4.624.319.312.864,23 | 2.150.423,05 | 3,85      |
| ARIMA (5,0,5)  | 1.823.035,46 | 4.830.373.834.662,80 | 2.197.811,15 | 3,91      |


---

## 🔁 Next Steps
- Explore multivariate models (including features like promotions, weather, etc.)
- Test machine learning and deep learning models (Prophet, XGBoost, LSTM)
- Automate the pipeline and export future forecasts
- Create interactive visual dashboards for business reporting

---

### 👨‍💻 About the Author

**André Rizzo**  
📊 Senior Data Scientist | Statistician | MBA in AI and Big Data (USP)  
🧠 Specialist in Machine Learning, Deep Learning and Predictive Modeling  
📍 Rio de Janeiro, Brazil  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrerizzo1)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?logo=github&logoColor=white)](https://github.com/andrerizzo)
[![Email](https://img.shields.io/badge/Email-andrerizzo@hotmail.com-D14836?logo=gmail&logoColor=white)](mailto:andrerizzo@hotmail.com)

---

*Last updated: March 30, 2025*
