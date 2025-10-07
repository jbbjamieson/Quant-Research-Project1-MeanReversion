# Quant Project 1: Mean Reversion Strategy

## Objective
Test if short-term price deviations in SPY revert to the mean.

## Method
- Download daily SPY prices (2015–2025)
- Compute 20-day rolling mean & std
- Generate z-score and trading signal
- Backtest naive long/short strategy

## Results
- Baseline Sharpe: -0.03
- Improvements: parameter tuning, transaction costs, multi-ticker
