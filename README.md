# Financial Portfolio Optimization & Market Data Suite

A comprehensive Python toolkit for quantitative financial analysis, market data retrieval, and portfolio optimization. This repository leverages modern portfolio theory (MPT) and advanced asset allocation models to construct, optimize, and visualize efficient investment portfolios.

## Features

- **Market Data Retrieval:** Automated fetching of historical stock prices and market capitalization data using `yfinance`.
- **Portfolio Optimization Models:**
  - **Markowitz Mean-Variance Optimization (MVO):** Maximizing the Sharpe ratio.
  - **Traditional Black-Litterman Model:** Incorporating market priors with absolute investor views.
  - **Bayesian Black-Litterman with Ledoit-Wolf Shrinkage:** Enhancing covariance matrix stability and estimation robustness using `PyPortfolioOpt`.
- **Performance Analytics & Visualization:** Generates efficient frontier comparison plots and performance metrics (Expected Return, Annual Volatility, and Sharpe Ratio).
- **Utility Functions:** Includes custom sequence generators and date-processing scripts for financial data wrangling.

---

## Prerequisites & Installation

Ensure you have Python installed, then install the required dependencies by running:

```bash
pip install yfinance pandas numpy matplotlib openpyxl PyPortfolioOpt requests
