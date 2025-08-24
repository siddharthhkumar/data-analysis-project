# 📊 FAANG+ Stock Analysis (2014-2024)

A comprehensive data analysis project examining a decade of performance for the top 10 technology companies.

##  Project Overview
This project analyzes the historical stock data of 10 major tech companies (FAANG+) from January 2014 to May 2024. The goal is to compare their growth, assess their risk profiles, and understand how they move in relation to each other in the market.

##  Key Insights & Findings
1.  **Top Performer:** NVIDIA (NVDA) demonstrated exceptional growth, significantly outperforming all other stocks in the analysis.
2.  **Highest Volatility:** Tesla (TSLA) and Netflix (NFLX) were the most volatile stocks, representing higher risk and potential reward.
3.  **Market Correlation:** Most stocks showed a strong positive correlation, often moving in tandem with broader market trends. PayPal (PYPL) and Netflix (NFLX) showed some of the weakest correlations to the group.
4.  **Biggest Drawdown:** Meta (META) and Netflix (NFLX) experienced the most severe peak-to-trough declines during market downturns, highlighting their higher risk profile.

##  Tech Stack & Methodology
- **Data Extraction:** Yahoo Finance API (`yfinance`)
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Environment:** Google Colab
- **Analysis Techniques:** Time Series Analysis, Normalization, Volatility Calculation, Correlation Analysis, Drawdown Analysis.

##  Repository Structure

faang-stock-analysis/
├── FAANG_Stock_Analysis.ipynb # Main Jupyter Notebook
├── README.md # Project documentation
└── images/ # Folder for exported visualizations
├── normalized_growth.png
├── volatility_barchart.png
└── correlation_heatmap.png


##  How to Run
1.  Open the `FAANG_Stock_Analysis.ipynb` file in [Google Colab](https://colab.research.google.com/).
2.  Click `Runtime` in the menu, then `Run all`.
3.  The code will execute sequentially, fetching live data and generating all visualizations.

##  Author
**Siddharth Kumar**
- [LinkedIn](https://www.linkedin.com/in/siddharth-kumar-0938ab245/)
- Email: Siddharthk1500@gmail.com

*This project was created to showcase data analysis skills using Python and financial data.*
