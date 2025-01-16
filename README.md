# ComputationalFinance_PortfolioManagement

This repository contains a MATLAB library and project report analyzing portfolio management strategies in computational finance. The study applies modern techniques to optimize portfolios based on the S&P 500 sector indices and factor indices, covering methodologies such as efficient frontier computation, robust portfolio construction, and risk optimization.

## Overview

### Objectives
1. **Efficient Frontier Analysis**: Compute and analyze efficient frontiers under various constraints.
2. **Robust Portfolio Strategies**: Address estimation errors using robust allocation methods.
3. **Factor Integration**: Leverage Principal Component Analysis (PCA) and Black-Litterman methods.
4. **Risk Management**: Optimize portfolios with Value at Risk (VaR) considerations.
5. **Diversification**: Evaluate and improve diversification in portfolio allocation.

### Key Features
- **Efficient Frontier Construction**: Analyze standard and constrained scenarios for portfolio optimization.
- **Robust Frontier Methods**: Utilize resampling techniques to address estimation errors.
- **Black-Litterman Framework**: Integrate market equilibrium and investor views for customized portfolio weights.
- **Diversification Metrics**: Evaluate portfolios using the Gini coefficient, Herfindahl index, and entropy measures.
- **Principal Component Analysis**: Reduce noise and capture primary variance drivers in asset returns.
- **VaR Optimization**: Incorporate tail risk measures into portfolio optimization strategies.

## Data and Methodology

### Dataset
- **Sector Indices**: Cyclical, defensive, and sensitive sectors from the S&P 500.
- **Factor Indices**: Momentum, Value, Growth, Quality, and Low Volatility.
- **Period**: January 2021 - October 2024.

### Models and Techniques
- Log-return analysis with normality tests (Shapiro-Wilk, Kolmogorov-Smirnov).
- Portfolio optimization under various constraints and scenarios.
- Out-of-sample performance evaluation for 2024.

### Metrics
- **Risk-Reward Measures**: Sharpe Ratio, Calmar Ratio.
- **Risk Metrics**: Volatility, Maximum Drawdown.
- **Diversification Metrics**: Entropy, Diversification Ratio.

## Results and Findings
- **Portfolio Performance**: Portfolios designed for Sharpe Ratio maximization delivered high returns but faced challenges in robustness and diversification.
- **Diversification-Oriented Portfolios**: Showed stability and effective risk distribution across market conditions.
- **Robust Approaches**: Enhanced resilience to estimation errors and outperformed standard methods in volatile conditions.
- **PCA and Black-Litterman**: Provided insightful strategies for integrating systematic factors and market views.

## Repository Structure
- **MATLAB Code**: Scripts for portfolio optimization, simulation, and performance evaluation.
- **Report**: A detailed document summarizing theoretical frameworks, methodologies, and results.

## References
- Fama and French (1992): "Common risk factors in the returns on stocks and bonds."
- Razali and Wah (2011): "Power comparisons of Shapiro-Wilk, Kolmogorov-Smirnov, Lilliefors, and Anderson-Darling tests."
- Market analysis from S&P Global and J.P. Morgan reports.

For further details, refer to the full project report in this repository.
