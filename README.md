📊 Reliance Stock Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Reliance Industries Limited stock data to understand price trends, volatility, trading volume, and moving average behavior using historical market data.

The analysis uses real stock data fetched programmatically via the Yahoo Finance API to ensure reproducibility and real-world relevance.

🎯 Objectives

Analyze long-term and short-term price trends

Study daily returns and stock volatility

Examine trading volume behavior

Identify trends using moving averages

📂 Dataset

Source: Yahoo Finance (via yfinance API)

Stock: Reliance Industries Limited (RELIANCE.NS)

Market: NSE (India)

Period: 2019 – 2024

Features:
Date

Open

High

Low

Close

Adjusted Close

Volume

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

yfinance

Jupyter Notebook

📈 Key Analysis Performed

Closing price trend analysis

Daily returns and volatility analysis

Trading volume analysis

20-day and 50-day moving average analysis

🔍 Key Insights

The stock shows long-term growth with periodic market corrections

Volatility increases during periods of market uncertainty

Volume spikes often align with significant price movements

Moving averages help identify trend shifts and momentum changes

📁 Project Structure
Reliance-Stock-EDA/
│
├── data/
│   └── reliance_stock.csv
├── notebooks/
│   └── reliance_stock_eda.ipynb
├── README.md
├── requirements.txt
└── .gitignore

🚀 How to Run the Project
pip install -r requirements.txt


Open the notebook:

notebooks/reliance_stock_eda.ipynb

🔮 Future Enhancements

Add CAGR and drawdown analysis

Compare with other NSE stocks

Build an interactive dashboard using Power BI

👤 Author

Mehak Choudhary
B.Tech Computer Science | Data Analysis & Python
