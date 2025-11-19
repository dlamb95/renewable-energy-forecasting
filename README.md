# Renewable Energy Forecasting

This project forecasts solar and wind energy production over time using public energy and weather datasets. The goal is to understand seasonal patterns and how temperature and climate variables influence renewable output.

---

## 📊 Data & Methods

### Data Sources
- U.S. Energy Information Administration (EIA)
- Weather data from CIMIS and related sources

### Methods
- Time series preprocessing  
  - Handling missing values  
  - Resampling and smoothing  
  - Creating lagged features
- Baseline models  
  - Seasonal naïve model  
  - Simple linear regression
- Forecasting models  
  - ARIMA  
  - SARIMA  

---

## 🛠 Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **Statsmodels** (ARIMA/SARIMA)
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## 🔍 Key Results & Insights
- Strong seasonal patterns observed across months and seasons  
- Temperature and irradiance correlate strongly with production  
- SARIMA models outperform naive baselines during peak seasons  
- Visualizations reveal predictable highs and lows in renewable output  

---

## 📂 Repository Structure

