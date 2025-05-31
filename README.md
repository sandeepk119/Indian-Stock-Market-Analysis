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

---

## 1. Project Overview
This project explores and compares the historical stock price trends of prominent companies listed on the National Stock Exchange (NSE) of India — including **CIPLA**, **Tata Consultancy Services (TCS)**, **Reliance Industries**, and **HDFC Ltd**.

The goal is to uncover patterns, trends, and insights through data analysis and visualization, using daily stock prices over several years. This is a beginner-friendly finance project built following the six-step data analysis process.

---

## 2. Objective.
To analyze stock trends, daily returns, volatility, and comparative performance of selected Indian companies from 2000 to 2021 in order to develop a foundational understanding of financial data and long-term investing behavior.

---

## 3. Key Questions (ASK Phase)

1. Which company among CIPLA, RELIANCE, HDFC, and TCS delivered the most consistent returns from 2000 to 2021, based on annualized return and standard deviation?  
2. How did each company’s 30-day moving average behave during major market stress periods (e.g., 2008 crisis, 2016 demonetization, 2020 COVID crash)?  
3. What was the maximum drawdown for each stock between 2000 and 2021, and how long did it take to recover?  
4. How does the average monthly return and volatility of each company compare, and what does this imply about risk-reward trade-offs?  
5. Which company offered the best risk-adjusted return (Sharpe Ratio) over the two decades?

---

## 4. Tools & Technologies
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, yfinance
- **Environment:** Jupyter Notebook (Kaggle or Spyder)

---

## 5. Folder Structure
<pre>
indian-stock-analysis/
├── data/                  # CSV files for CIPLA, HDFC, RELIANCE, TCS
├── analysis.ipynb         # Main Jupyter Notebook (complete analysis)
├── visuals/               # Plots and charts
└── README.md              # Project documentation
 </pre>

---

## 6. Project Phases

1. **ASK** – Define objective, stakeholders, and key metrics  
2. **PREPARE** – Collect and organize data (Kaggle/NIFTY50)  
3. **PROCESS** – Clean and format data for analysis  
4. **ANALYZE** – Perform statistical analysis and compute financial metrics  
5. **SHARE** – Visualize findings and explain insights  
6. **ACT** – Summarize key takeaways and outline future direction

---

## 7. Companies Analyzed
- **CIPLA**
- **Tata Consultancy Services (TCS)**
- **Reliance Industries**
- **HDFC**

---

## 8. Sample Visualizations

- Time series of closing prices  
- Daily returns comparison  
- Moving average overlays  
- Volatility (standard deviation of returns)  
- Drawdown and recovery periods  
- Sharpe ratio vs. return/volatility

---

## 9. How to Run This Project
1. Clone or download this repository.
2. Open the `analysis.ipynb` notebook in Jupyter (via Anaconda, Kaggle, or Google Colab).
3. Ensure the following Python libraries are installed:

    ```
    pandas
    numpy
    matplotlib.pyplot
---

## 10. Dataset Sources
Nifty 50 Stock Data on Kaggle [LINK](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data/data)

---

## 11. Author
Sandeep Kumar 
Aspiring Data Analyst | Exploring Finance through Data

---

## 12. License
This project is open-source and free to use for educational purposes.

---

## 13. Conclusion

This project applied a data-driven approach to analyze the long-term performance of four major Indian stocks — CIPLA, HDFC, RELIANCE, and TCS — from 2000 to 2021. Through five SMART questions, we explored consistency, volatility, crisis behavior, downside risk, and risk-adjusted returns.

### 🏆 Final Rankings (Overall Score Summary)

| Rank | Company   | Investor Profile                        |
|------|-----------|------------------------------------------|
| 🥇 1 | **HDFC**      | Growth-Oriented (High return, high risk) |
| 🥈 2 | **RELIANCE**  | Balanced (Moderate risk and return)      |
| 🥉 3 | **TCS**       | Conservative (Low volatility, stable gains) |
| 🚩 4 | **CIPLA**     | Speculative (Low return, high risk)      |

HDFC stood out as a top performer with the highest return and Sharpe Ratio but at the cost of high volatility. TCS delivered consistent, stable results ideal for conservative investors, while RELIANCE balanced both well. CIPLA lagged in return and recovery, making it the riskiest pick.

This analysis highlights how historical price behavior and risk-adjusted metrics can guide more informed investment decisions.

---

## 14. What’s Next?

- Add technical indicators (RSI, Bollinger Bands, MACD)
- Compare other NIFTY50 stocks or sector-specific performance
- Build an interactive dashboard using Streamlit or Dash
- Expand to include fundamental metrics like P/E, EPS, and ROE
