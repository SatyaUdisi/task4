# Real-World Financial Data Analytics Project

## 📈 1. Domain Background & Data Preprocessing
This project conducts an end-to-end time-series analysis on the historical performance of market equities utilizing public financial ledger datasets.
* **Feature Engineering:** Implemented rolling window statistical operations to compute 7-day and 30-day Simple Moving Averages (SMA) to smooth out micro-volatility and extract underlying market momentum.
* **Volatility Profiling:** Derived daily percentage deltas to model standard distribution profiles of trading risks.

## 📊 2. Trend Visualizations
The analysis generated two key diagnostic dashboards to visualize long-term and short-term financial trajectories:

### Market Momentum & Support Lines:
![Stock Price Analysis](stock_trend_analysis.png)

### Risk and Return Spreads:
![Volatility Distribution](stock_volatility_distribution.png)

## 🎯 3. Core Strategic Conclusions
* **Trend Convergence:** The crossover where the short-term 7-Day MA moves above or below the 30-Day MA provides clean, actionable technical entry and exit signals for portfolio allocations.
* **Stability Insights:** The daily returns chart reveals a stable, normal distribution tightly centered around 0%, indicating consistent consolidation with limited outlier spikes during this market cycle.
