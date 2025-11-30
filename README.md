
📁 Stock-Market-Analysis
│── A.csv, AA.csv, AAAU.csv, AACG.csv, AADR.csv, AAL.csv, AAXJ.csv, ABEQ.csv, symbols_valid_meta.csv
│── stock_analysis.py
│── README.md
│── /plots
│     │── closing_price.png
│     │── moving_averages.png
│     │── returns_distribution.png
│     │── volatility.png
│     │── dashboard_grid.png
📈 Stock Market Analysis Using Python

symbols_valid_meta – Time Series, Statistics, Visualization & Mini Dashboard

This project performs a complete exploratory data analysis (EDA) onsymbols_valid_meta's stock data using Python.
It includes trend analysis, volatility measurement, distribution study, correlation heatmaps, and a 4-panel dashboard built using Matplotlib & Seaborn.

---

🗂 Project Overview

This repository contains a comprehensive stock market analysis workflow:
✅ 1. Data Loading
[A.csv](https://github.com/user-attachments/files/23838263/A.csv)
[AA.csv](https://github.com/user-attachments/files/23838265/AA.csv)
[AAAU.csv](https://github.com/user-attachments/files/23838267/AAAU.csv)
[AACG.csv](https://github.com/user-attachments/files/23838269/AACG.csv)
[AADR.csv](https://github.com/user-attachments/files/23838297/AADR.csv)
[AAL.csv](https://github.com/user-attachments/files/23838280/AAL.csv)
[AAXJ.csv](https://github.com/user-attachments/files/23838282/AAXJ.csv)
[ABEQ.csv](https://github.com/user-attachments/files/23838287/ABEQ.csv)
[symbols_valid_meta.csv](https://github.com/user-attachments/files/23838291/symbols_valid_meta.csv)

Dataset: A.csv, AA.csv, AAAU.csv, AACG.csv, AADR.csv, AAL.csv, AAXJ.csv, ABEQ.csv, sym
bols_valid_meta.csv

Converted Date
to datetime Set Date as index


✅ 2. Basic Inspection

Displayed head, info, and descriptive statistics
Understood structure & quality of the dataset


✅ 3. Daily Return Analysis

Calculated:
Mean return
Median return
Standard deviation
Variance
Skewness
Kurtosis
This reveals how the stock moves on a daily basis and how risky/volatile the returns are.

✅ 4. Moving Averages (Trend Detection)

Added:

20-Day Moving Average (MA20)
50-Day Moving Average (MA50)
Used to identify short-term and mid-term trends.

✅ 5. Volatility Analysis

Computed 20-day rolling standard deviation to measure risk over time.

✅ 6. Data Visualization
Created professional and clean visual plots:

Closing price trend
Moving average trend
Daily return distribution
Outlier detection (boxplot)


✅ 7. Mini Dashboard (4-Plot Grid)
A compact financial dashboard including:
[file:///D:/C%20DRIVE%20PART/Downloads/STOCK%20MARKET%20ANALYSIS.html]
1. Closing Price
2. MA20 vs MA50
3. Daily Return Histogram
4. 20-Day Volatility Curve
---
🛠 Tech Stack

Tool	Purpose
Python	Programming
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Plotting
Seaborn	Advanced visualization
SciPy	Statistical analysis
[STOCK MARKET ANALYSIS.ipynb](https://github.com/user-attachments/files/23838242/STOCK.MARKET.ANALYSIS.ipynb)
<img width="4800" height="3600" alt="A_dashboard" src="https://github.com/user-attachments/ass
ets/ca30c739-07e1-4e52-856f-67cac0633413" />
<img width="4800" height="3600" alt="AA_dashboard" src="https://github.com/user-attachments/assets/775f9203-e85b-4d13-b1e4-6b1f5d67d97b" />
<img width="4800" height="3600" alt="AAAU_dashboard" src="https://github.com/user-attachments/assets/0ce0ab5b-5a6d-4684-b9d6-352966eae0ff" />
<img width="4800" height="3600" alt="AACG_dashboard" src="https://github.com/user-attachments/assets/a1be5dcc-62b9-4345-9f37-cce008d4c699" />
<img width="4800" height="3600" alt="AADR_dashboard" src="https://github.com/user-attachments/assets/76365a9e-3dd1-49bb-b32a-78c57343e858" />
<img width="4800" height="3600" alt="AAL_dashboard" src="https://github.com/user-attachments/assets/43fcc0ec-0477-4eeb-a1de-1e3abaad3215" />
<img width="4800" height="3600" alt="AAXJ_dashboard" src="https://github.com/user-attachments/assets/f352979a-6de6-4d49-8d32-0cfc0ae813b0" />
<img width="4800" height="3600" alt="ABEQ_dashboard" src="https://github.com/user-attachments/assets/f6fb1387-d1de-4f86-a8ee-def7a82e2d57" />
