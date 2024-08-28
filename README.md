# Portfolio Optimization with Machine Learning

## Project Overview
This project focuses on optimizing a diversified portfolio using machine learning techniques and financial data analysis. It explores various portfolio strategies, including mean-variance optimization, equal-weight strategy, and evaluates them under different market conditions through simulations and sensitivity analysis.

## Project Structure

### Data Collection
- Historical stock prices are fetched using the `yfinance` library for selected Nifty 50 stocks.
- The data is processed to calculate expected returns, covariance matrices, and other financial metrics.

### Portfolio Optimization

- **Mean-Variance Optimization:**
  - Implements Markowitz’s mean-variance optimization to compute optimal asset weights that maximize returns for a given level of risk.
  
- **Equal-Weight Strategy:**
  - A simple strategy where each asset in the portfolio is assigned an equal weight.

### Performance Evaluation

- **Sharpe Ratio:**
  - Measures the risk-adjusted return of each portfolio strategy.
  
- **Diversification Ratio:**
  - Evaluates the degree of diversification in the portfolio.
  
- **Drawdown Analysis:**
  - Assesses the maximum drawdown to understand the potential risk of significant losses.

### Scenario Simulations

- **Market Crash Scenario:**
  - Simulates the impact of a hypothetical market crash on portfolio performance.
  
- **Monte Carlo Simulations:**
  - Projects possible future portfolio values under various scenarios, providing a probabilistic understanding of portfolio risk.

### Sensitivity Analysis

- **Interest Rate and Inflation Shocks:**
  - Evaluates the portfolio's sensitivity to external economic factors such as interest rate hikes or inflation shocks.

### Sector and Factor Exposures

- Analyzes how the portfolio is exposed to different sectors and financial factors, allowing for a deeper understanding of the portfolio’s risk profile.

## Results
- The notebook provides visualizations and metrics comparing the performance of different portfolio strategies.
- Detailed sensitivity analysis is included to assess how robust the portfolio is to changes in external factors.
- Simulation results demonstrate the potential future performance of the portfolio under various conditions.
