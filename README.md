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
- Implied volatility 
- Out-of-the-money put options tend to have higher implied volatility than near-the-money options.
- The implied volatility surface changes across maturities, reflecting the term structure of option-implied risk.

I chose two expiration dates, 2026-06-12 and 2026-08-21, while the time of observation is 2026-05-13. The implied volatility curves for both call and put options is not constant across strikes.

One possible explanation is that investors anticipate potential market downturns, which increases the demand for out-of-the-money put options. This higher demand raises their prices and thus their implied volatilities. Through the put–call parity relationship, this also affects call prices. In addition, options with longer times to expiration tend to have higher implied volatilities because uncertainty about the underlying asset’s future price grows with time.

We also observe that the implied volatility of put options is higher than that of call options. Although put–call parity ensures consistency between option prices, investors’ stronger demand for downside protection lead to slightly higher implied volatilities for puts than for calls.
