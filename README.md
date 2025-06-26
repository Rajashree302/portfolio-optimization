📊 Portfolio Optimization using Python
This project simulates and optimizes a stock portfolio based on historical data. It calculates the optimal asset allocation to maximize returns while minimizing risk, using Monte Carlo simulation, Sharpe Ratio, and Value at Risk (VaR). The project includes performance backtesting and visualization.

📌 Objective
To build a diversified portfolio of 5 stocks and:

Simulate 10,000+ random portfolios
Identify the portfolio with the highest Sharpe Ratio
Backtest the optimized portfolio
Calculate Value at Risk (VaR)
Compare performance with a benchmark like S&P 500
📈 Key Features
✅ Monte Carlo Simulation of Portfolio Weights
✅ Sharpe Ratio Optimization
✅ Risk-return Visualization
✅ 📉 Backtested Cumulative Return Chart
✅ 📊 VaR Calculation (95% Confidence Level)
✅ Benchmark Comparison (Optional: S&P500/Nifty50)
🧠 Methodology
Data Collection

Used yfinance to fetch stock data (2020-2023)
Selected 5 diversified stocks: Apple, Google, Amazon, JPMorgan, Coca-Cola
Simulation & Optimization

Generated 10,000 portfolios with random weights
Computed expected return, volatility, and Sharpe Ratio
Identified the portfolio with the best Sharpe Ratio
Backtesting

Applied optimal weights on real data
Calculated cumulative returns over 3 years
Visualized portfolio performance
Risk Estimation

Computed daily returns of the optimized portfolio
Calculated Value at Risk (VaR) at 95% confidence level
🧮 Tech Stack
Python
Jupyter Notebook
Libraries:
pandas, numpy, matplotlib, seaborn
scipy.optimize, yfinance
📂 Folder Structure
💡 Insights
Sharpe Ratio achieved: 1.34
Portfolio outperformed S&P 500 over 3 years
Maximum 1-day Value at Risk (95%): -$150
