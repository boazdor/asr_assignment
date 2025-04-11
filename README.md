# Investment Portfolio Simulator

This Python-based tool allows users to manage and forecast the performance of an investment portfolio. It supports adding assets, analyzing portfolio composition, visualizing historical price trends, and simulating future portfolio value using Monte Carlo simulations based on geometric Brownian motion.

---

## Features

- Add assets to the portfolio with sector, asset class, quantity, and purchase price
- Retrieve historical and current price data using the `yfinance` API
- Display current portfolio composition and value
- Show breakdown of value by asset, sector, and asset class
- Plot historical price movements
- Simulate 5-year portfolio forecasts using geometric Brownian motion
- Visualize simulation results with quantile bands (5%, 50%, 95%)

---

## Requirements

Ensure the following Python packages are installed:

yfinance, pandas, matplotlib, numpy

---

## Notes

- Historical and real-time data are downloaded from Yahoo Finance using the `yfinance` library.
- Forecasting assumes independent asset behavior and is based on historical returns and volatilities.

---

# Possible Improvements

- Introduce correlation between assets in the simulation
- Add support for dividend reinvestments and cash flows
- Add economic trends into the forecasting model
- Implement transaction logging and portfolio rebalancing
- Export reports to CSV or PDF
- Add historic portfolio performance and benchmark
