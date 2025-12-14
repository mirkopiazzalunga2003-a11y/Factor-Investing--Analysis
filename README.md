# Factor Investing Report  

## Overview
This repository contains the Python code and empirical analysis for the project *“Constructing Portfolios through Factor-Based ETFs”*  
The study evaluates **MSCI USA factor indices** aligned with the **Fama–French five-factor model** (Market, SMB, HML, RMW, CMA), using the **MSCI USA INDEX as benchmark** over **1999–2024**.

---

## Scope of Analysis
This research focuses on the analysis of the indices most exposed to the five factors of Fama and French.
The goal is to build portfolios capable of maximizing returns or minimizing volatility, in function
of the investor's risk appetite.
The analysis will focus on the American market, using the S&P 500 as a benchmark.
Model portfolios will be built from a predefined investment share in the benchmark, in
this case of 50%, with an optimization of the weights of the selected indices, in order to obtain results
higher than investing in the benchmark alone.

## index of the analyses carried out
- **Performance metrics:** cumulative/rolling returns, volatility, Sharpe & Sortino ratios, drawdowns, VaR, correlation  
- **Factor exposure:** linear regressions on Fama–French 5-factor US data  
- **Portfolio construction:** efficient frontier optimization considering the last 10 and 25 years for the analysis
- **Forecasting & strategies:** SARIMAX on log-returns; CAPM model based on beta; SMA/EMA vs buy-and-hold  

---

## Data
- **MSCI USA indices (monthly, gross returns) downloaded by official MSCI website:**  
  S&P 500, Small Cap, Value, Growth, Small Cap Value, Quality, Min Volatility, High Dividend, Multifactor  
- **Fama–French 5-Factor US dataset** (1963–present)  
- Dataset links and Colab notebook provided in the report

--- 

## Author

**Mirko Piazzalunga**

