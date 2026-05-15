# Implied-Volatility-Smile-Project

This project analyzes SPY option prices and extracts implied volatility using the Black-Scholes model. The objective is to study how implied volatility varies across strike prices and maturities.

## Data
- Call and put options of SPY
- Source: yfinance
- Maturities: Selected expirations around 1 month and 3 months

## Methods
- Black-Scholes model
- Visualize implied volatility against strike prices


## Main Findings
- Implied volatility is not constant across strikes.
- Out-of-the-money put options tend to have higher implied volatility than near-the-money options.
- The implied volatility surface changes across maturities, reflecting the term structure of option-implied risk.
