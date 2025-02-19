# Algorithmic Trading: Mean Reversion & Momentum Strategies

## Overview
This project implements and backtests two algorithmic trading strategies:
- **Mean Reversion Strategy (Bollinger Bands)**
- **Momentum Strategy (Moving Average Crossover)**

## Performance Summary
| Strategy          | Sharpe Ratio | Max Drawdown | Final Portfolio Value ($) |
|------------------|-------------|--------------|--------------------------|
| Mean Reversion   | 0.33        | -9.24%       | $11,589.40               |
| Momentum         | 0.04        | -50.78%      | $9,060.15                |

## How to Run
1. Install dependencies:
   ```sh
   pip install numpy pandas yfinance matplotlib tabulate

## Results
- **The Mean Reversion Strategy outperformed the Momentum Strategy with a higher Sharpe Ratio and lower drawdown.
- **The Momentum Strategy suffered from high volatility and large losses.
