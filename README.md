# Quant
All-in-one open-source quant library that values simplicity and elegance, to democratize those 'proprietary techniques'.

## Philosophy
Build and a set of clean APIs that simplify the daily routine part and cliches of a quant's job and help you better focus on what are really important, which is the structure design.

## Installation
```python
pip install quant
```

## Hello World
```python
import quant as qt
qt.bsm_option_pricer(type = 'eu',strike = '10',vol = 0.2,expiration = '365') - Needs Improvements
```

## Core Functions
1. Option Pricing
   - Equity (Vanilla, Binary, Lookback, Asian)
   - Fixed Income (Swap, Cap/Floor, Swaptions)
   - Other Tools (Vasicek estimation, Debt pricing)
   - BSM 
   - Binary Tree
   - Monte-carlo Simulation
2. Visualization
   - Profit Graph for Options Strategies
3. Backtesting
4. Trading Strategies
   - Pair Trade
   - Multi-factors
5. Arbitrage Finder
   - Statistical Arbitrage
   - Convertible Bonds Arbitrage
   - Triangle Arbitrage

## References
1. DerivaGem 3.0 by 'Wall Street Bible'
2. Matlab Quant Finance Model
