📌 IndiaPulse — India’s Economic Intelligence System
📊 Overview

IndiaPulse is a data-driven economic intelligence system that tracks India’s inflation, fuel prices, RBI policy, and currency movement to detect economic stress and macroeconomic trends.

This project uses real Indian economic data to analyze:

Inflation dynamics

Fuel price shocks

RBI policy effects

Economic crises like COVID-19 and inflation surges

It replicates how central banks and economic research organizations analyze national economies.

🧠 What This Project Does

IndiaPulse answers questions like:

Does fuel inflation drive consumer inflation?

Does RBI interest rate control inflation?

When was India under economic stress?

How severe was the COVID and 2022 inflation crisis?

It produces:

An Economic Stress Index

Shock detection using Z-scores

Time-series visualizations

Lag and trend analysis

📁 Data Sources
Data	Source
CPI (Inflation)	FRED (OECD India CPI)
Petrol & Diesel	Retail fuel price dataset
USD/INR	FRED (USD-INR exchange rate)
NIFTY 50	Yahoo Finance
RBI Repo Rate	RBI historical policy data

All datasets were cleaned, aligned to monthly frequency, and merged for analysis.

🔧 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

🧩 Methodology
1️⃣ Data Engineering

Cleaned and aligned multiple macro-economic datasets

Converted daily & event-based data into monthly time-series

2️⃣ Feature Engineering

Created:

Monthly inflation rate

Fuel price change

Stock market returns

Currency movements

3️⃣ Economic Analysis

Correlation analysis

Lag analysis (delayed impact of fuel & RBI)

Rolling averages (long-term trends)

4️⃣ Shock Detection

Used Z-scores to detect:

Inflation shocks

Energy price shocks

5️⃣ Stress Index

Created an India Economic Stress Index that measures:

How unstable India’s economy was each month.

📈 Key Insights

CPI inflation in India is not strongly driven by fuel prices in the short run

RBI interest rate changes affect inflation with a delay

COVID-19 and 2022 inflation crisis show up as major stress spikes

India’s inflation is dominated by food and structural factors, not petrol alone

🏆 Why This Project Is Special

Most student projects predict:

House prices, stock prices, customer churn

IndiaPulse analyzes:

The entire Indian economy

This makes it:

Macro-economic

Business-relevant

Government-grade analytics

▶ How to Run

Clone the repository

Install dependencies:

pip install pandas numpy matplotlib seaborn


Open IndiaPulse.ipynb

Run all cells from top to bottom

📌 Author

Devansh Sharma
Aspiring Data Analyst / Data Scientist
