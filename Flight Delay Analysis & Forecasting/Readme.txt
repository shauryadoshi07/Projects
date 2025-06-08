✈️ Flight Delay Analysis & Forecasting
Data Analysis Project — June 2025

📋 Project Overview
This project involves performing exploratory data analysis (EDA) and time series forecasting on flight delay data. The goal is to understand patterns in arrival and departure delays across different airlines, airports, and seasons, and to forecast future delays using ARIMA models.

The project demonstrates the full pipeline:
Data cleaning & preprocessing
Feature engineering
Data visualization
Correlation & covariance analysis
Time series decomposition & forecasting
Interactive visual insights

🗂️ Dataset
Source: FlightDelay.csv
Rows: ~5.8 million flight records
Columns: 31 features including:
YEAR, MONTH, DAY, DAY_OF_WEEK
AIRLINE, ORIGIN_AIRPORT, DESTINATION_AIRPORT
DEPARTURE_DELAY, ARRIVAL_DELAY, WEATHER_DELAY, AIRLINE_DELAY, etc.

🛠️ Tools & Libraries
Python
Pandas
NumPy
Seaborn
Matplotlib
Statsmodels (ARIMA, seasonal decomposition)
Scipy

🔍 Analysis Workflow
1️⃣ Data Cleaning & Feature Engineering
Handled missing values.
Mapped airline codes to full airline names.
Created new categorical feature season based on month.
Created DATE column for time series analysis.
2️⃣ Exploratory Data Analysis
Visualized arrival delays and departure delays:
Density plots
Boxplots
Violin plots
Scatterplots (with departure vs arrival delay)
Delay trends across day of week, month, and airline.
Correlation matrix and covariance matrix for key delay factors.
3️⃣ Time Series Analysis & Forecasting
Grouped arrival delay data daily.

Performed:
Time series decomposition: trend, seasonality, residuals.
ACF & PACF analysis.
ARIMA modeling and 31-day forecast.
Visualized forecasted delay trends.

📈 Key Visual Insights
Arrival delays strongly correlated with departure delays (~0.96).
Certain airlines consistently showed higher delays.
Weekends and specific months (winter) exhibited different delay patterns.
ARIMA modeling captured trends effectively for forecasting.
