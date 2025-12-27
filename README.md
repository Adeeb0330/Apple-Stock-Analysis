📊 Apple Stock Price Analysis Dashboard
📌 Project Overview

Analysed Apple stock daily price data sourced from Yahoo Finance using the yfinance API. Performed data cleaning and feature engineering in Python, including intraday volatility, open–close returns, and volume changes. Built an interactive Power BI dashboard to visualise trends and performance.

The goal of this project is to demonstrate data analysis, feature engineering, and BI dashboarding skills rather than trading or investment advice.

🧰 Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & feature engineering

Power BI Desktop – Dashboard creation & visualisation

Dataset – Yahoo Finance Historical Apple stock price data

📂 Dataset Description

The dataset contains daily stock market data with the following fields:

Date

Open

High

Low

Close

Volume

🔧 Feature Engineering (Calculated Metrics)

The following analytical columns were created to enhance insights:

Intraday Volatility (%)
Measures daily price fluctuation using the High–Low range.

OC_Change (%) (Open–Close Change)
Indicates intraday return and market sentiment.

OC_Direction
Categorises trading days as Up, Down, or No Change.

Volume Change (%)
Measures day-over-day change in trading activity.

Yearly and Monthly Returns %
See the yearly and monthly returns for analysis

📊 Power BI Dashboard Highlights

The Power BI dashboard provides:

📈 Close Price Trend over time

📉 Daily Open–Close Return Analysis

📊 Trading Volume Trend

🧮 KPI Cards:

Max and Min of Close Price

Average Daily Return

Average Intraday Volatility

🗓 Date Slicer for dynamic time-based analysis

📋 Detailed Daily Returns Table

🧠 Key Insights

Identifies daily market sentiment through Open–Close movement

Highlights periods of high volatility

Shows the relationship between price movement and trading volume

Enables quick performance assessment using KPIs

🎯 Use Case

This project is suitable for:

Data Analyst portfolio demonstration

Financial data analysis practice

Business-style stock performance reporting

⚠️ This project is for analytical and educational purposes only and does not provide financial or investment advice.

🚀 How to Use

Clone or download this repository

Open the Power BI .pbix file in Power BI Desktop

Explore the dashboard using the date slicer

Review Python scripts / CSV files for data preparation
