# Computational-Project---Portfolio-Optimization
Implemented and compared portfolio optimization models (MVO, Robust MVO, Risk Parity, Market-Cap Weighted) on S&amp;P 500 data using MATLAB. Applied rolling windows for out-of-sample tests, evaluated risk-return tradeoffs, and visualized results. Robust MVO showed downside protection, Risk Parity delivered stable long-term performance.

This project implements and compares four portfolio optimization methods in MATLAB:

1. Mean-Variance Optimization (MVO)
2. Robust Mean-Variance Optimization (box & ellipsoidal uncertainty sets)
3. Risk Parity Optimization
4. Market-Cap Weighted Portfolio (benchmark)

## Dataset
- 20 stocks from S&P 500
- Monthly adjusted closing prices (2007-12 to 2011-06)

## Methods
- Rolling 6-month estimation window
- Out-of-sample test from 2011-07 to 2011-11
- Performance metrics: Return, Variance, Std Dev, Sharpe Ratio
- Robust MVO tested under 90% and 95% confidence levels

## Results
- Plotted cumulative wealth curves and Sharpe ratios across strategies
- Robust MVO provided better downside protection
- Risk Parity delivered the most stable performance in the long run
- Market-cap weights served as a baseline benchmark
