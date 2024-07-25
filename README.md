## Computational_Finance_for_Asset_and_Portfolio_Management

#### Overview
This is a Academic project of Data Science Pos Degree which involves investigating the empirical properties of financial market returns using US stock market data and testing the performance of various portfolio investment strategies.

#### Activities and Techniques Covered: Heuristic and Markowitz Modern Portfolio Management Investment Strategies

1. **Data Selection**
   - For this project we've settled 11 S&P 500 listed stocks, one per each of the 11 different sectors and fetch the market data from 01-01-2010 to 31-12-2022.

2. **Return Computation**
   - The time series was calculated in daily, weekly, and monthly log-returns using adjusted closing prices.

3. **Empirical Investigation**
   - Analyzed financial market return properties:
     - Absence of auto-correlation
     - Fat Tails (non-normal distribution)
     - Asymmetry or negative skewness
     - Volatility clustering
     - Leverage effects
     - Conditional non-normality

4. **Performance Evaluation**
   - Splitted data into training (01-01-2010 to 31-12-2015) and test (01-01-2016 to 31-12-2022) sets.
   - Evaluated investment strategies:
     - Buy & Hold
     - Equally weighted portfolio
     - Quintile portfolio
     - Markowitz’s mean-variance portfolio (no short-selling)
     - Global Minimum Variance Portfolio (no short-selling)
     - Maximum Sharpe ratio portfolio
     - Inverse Volatility Portfolio

EXTRA: we also investigated the performance of portfolio management strategies using alternative risk measures, e.g., downside risk, Value-at-Risk (VaR), Conditional VaR (CVaR) or expected shortfall (ES).

5. **Case Study Report**
   - Discuss results using risk-adjusted performance metrics (returns, volatility, Sharpe ratio, Sterling ratio, drawdown).
