🌞 Renewable Energy Forecasting

Predicting solar and wind production using time-series modeling and environmental variables.

📘 Overview

This project analyzes and forecasts renewable energy production (solar and wind) using historical U.S. Energy Information Administration (EIA) data combined with weather features sourced from CIMIS. The goal is to understand seasonal trends, identify key environmental drivers, and build interpretable forecasting models using traditional statistical approaches (ARIMA/SARIMA) and regression techniques.

The project supports energy planning, load forecasting, and sustainability analytics by demonstrating how temperature, seasonality, and irradiance patterns influence renewable output.

📂 Project Objectives

Clean and prepare large-scale historical energy production data

Integrate weather factors relevant to renewable generation

Explore seasonality and long-term trends

Build baseline and advanced forecasting models

Visualize production patterns and model performance

🔍 Data Sources
Energy Data

U.S. Energy Information Administration (EIA)

Annual and monthly renewable energy production

Solar and wind generation data

Weather Data

CIMIS (California Irrigation Management Information System)

Temperature

Solar irradiance

Humidity

Wind speed

🧹 Data Preparation

Key preprocessing steps include:

Cleaning missing or inconsistent values

Converting date fields into time-series format

Resampling to align frequencies (daily, monthly)

Creating lag features (t−1, t−12, etc.)

Merging energy and weather datasets on location and date

Visualizing distributions and trends prior to modeling

🔧 Methods & Modeling
Exploratory Analysis

Seasonal and monthly production curves

Correlation between weather variables and energy output

Time-series decomposition (trend + seasonality + noise)

Forecasting Models

Seasonal Naïve Baseline

Regression Models

Temperature → production

Irradiance → solar production

ARIMA and SARIMA

Automatically selected parameters (p,d,q)(P,D,Q)s

Strong performance on seasonal datasets

Model Evaluation

Train/test split across time

MAPE, RMSE, MAE metrics

Visual overlays of predictions vs. actuals

📈 Key Insights

Solar production exhibits clear annual seasonality, with predictable summer peaks.

Wind patterns vary more widely but maintain seasonal cycles across regions.

Temperature and solar irradiance show strong positive correlation with renewable output.

SARIMA models outperform baseline models during high-variability months.

Combined energy + weather datasets yield improved forecasting accuracy over using energy alone.

🛠 Tech Stack

Python 3

Pandas, NumPy

Statsmodels (ARIMA/SARIMA)

Matplotlib, Seaborn

Jupyter Notebook
