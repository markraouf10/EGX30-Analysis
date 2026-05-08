# EGX30 Historical Analysis

Historical analysis of the Egyptian Exchange EGX30 index covering exploratory data analysis, technical indicators, and ARIMA forecasting.

## Time Period Analyzed
January 2014 to May 2026 (12 years, 3,000 trading days)

## Project Overview
This project analyzes 12 years of EGX30 daily price data to uncover behavioral patterns, risk characteristics, and return dynamics of the Egyptian stock market.

## Key Findings
- Total return of 666.9%% over 12 years
- Maximum drawdown of -52.85%% bottoming on July 5, 2022
- Ramadan effect confirmed: -0.054%% avg return during Ramadan vs +0.080%% outside
- Sharpe ratio of -0.45 using Egyptian T-bill rate of 27%%
- ARIMA(0,0,2) achieves 59.56%% directional accuracy on test set
- Returns show near weak-form efficiency (minimal autocorrelation)

## Project Structure
- EGX30_Analysis.ipynb - Full project notebook (Phases 3-7)
- data/ - Raw dataset (EGX_30_Historical_Data.csv) sourced from Investing.com
- figures/ - All 15 generated charts
- report/ - IEEE format report (PDF) and PowerPoint presentation
- dashboard/ - Power BI dashboard (.pbix) and screenshot

## Analysis Phases
1. Data Loading and Inspection
2. Data Preprocessing and Cleaning
3. Exploratory Data Analysis (10 sections)
4. Feature Engineering (33 technical indicators)
5. ARIMA Forecasting and Residual Diagnostics

## Tools and Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn, Power BI

## Institution
Arab Academy for Science, Technology and Maritime Transport (AAST)
Data Analysis Course - 2026
