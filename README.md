# Indian Stock Market Analysis
Analyzing Trends and Performance of Key NSE Listed Companies

## Table of Contents
1. Project Overview
2. Objective
3. Key Questions (Ask Phase)
4. Tools & Technologies
5. Folder Structure
6. Project Phases
7. Companies Analyzed
8. Sample Visualizations
9. How to Run This Project
10. Dataset Sources
11. Author
12. License
13. Conclusion
14. Next Steps


## 1. Project Overview
This project explores and compares the historical stock price trends of prominent companies listed on the National Stock Exchange (NSE) of India — such as Hindustan Aeronautics Ltd (HAL), Tata Consultancy Services (TCS), Reliance Industries, and HDFC Bank.

The goal is to uncover patterns, trends, and insights through data analysis and visualization, using daily stock prices over several years. This is a beginner-friendly finance project built following the six-step data analysis process.

## 2. Objective
To analyze stock trends, daily returns, volatility, and comparative performance of selected Indian companies to develop a foundational understanding of financial data.

## 3. Key Questions (ASK Phase)
- How have the selected companies performed over the years?
- Which company shows the highest volatility?
- Are there any patterns or seasonality in price movements?
- How can indicators like moving averages help identify trends?

## 4. Tools & Technologies
- Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, yfinance
- Environment: Jupyter Notebook (Kaggle or Spyder)

## 5. Folder Structure
<pre>
indian-stock-analysis/
├── data/                  # Stock data files (CSV)
├── notebooks/             # All steps in the data analysis process
│   ├── 1_Ask_Phase.ipynb
│   ├── 2_Prepare_Data.ipynb
│   ├── 3_Process_Data.ipynb
│   ├── 4_Analyze_Data.ipynb
│   ├── 5_Share_Findings.ipynb
│   └── 6_Act_Insights.ipynb
├── visuals/               # Plots and charts
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
</pre>

## 6. Project Phases
1. **ASK** – Define objective, stakeholders, and key metrics
2. **PREPARE** – Collect data via Yahoo Finance or Kaggle (NIFTY50 dataset)
3. **PROCESS** – Clean and format stock price data
4. **ANALYZE** – Explore trends, volatility, daily returns, and comparisons
5. **SHARE** – Present visualizations and findings
6. **ACT** – Summarize conclusions and propose potential next steps

## 7. Companies Analyzed
- Hindustan Aeronautics Ltd (HAL)
- Tata Consultancy Services (TCS)
- Reliance Industries
- HDFC Bank

## 8. Sample Visualizations
- Time series of closing prices
- Daily returns comparison
- Moving average overlays
- Volatility (standard deviation of returns)

## 9. How to Run This Project
1. Clone this repo
2. Install dependencies:
    > pip install -r requirements.txt
3. Launch Jupyter Notebook and explore the notebooks in order.

## 10. Author
Sandeep Kumar 
Aspiring Data Analyst | Exploring Finance through Data

## 11. Dataset Sources
Nifty 50 Stock Data on Kaggle [LINK](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data/data)

## 12. License
This project is open-source and free to use for educational purposes.

## 13. Conclusion
> To be added

## 14. What’s Next?
Adding more technical indicators (e.g., RSI, Bollinger Bands)

Expanding to sector-based comparisons

Building an interactive dashboard using Streamlit (optional)
