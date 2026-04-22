# options-pricing-volatility-surface

This project implements option pricing using the Black-Scholes model and extracts implied volatility from real market data.

## Features

- Black-Scholes pricing model
- Implied volatility calculation (Newton-Raphson + Bisection fallback)
- Volatility smile (moneyness-based)
- Volatility surface (strike, maturity, IV)
- Pricing of new options using interpolated implied volatility
- Term structure of interest rates (short, medium, long)

## Data

Market data is obtained using yfinance.

## Key Insights

- Implied volatility is not constant and depends on strike and maturity
- The volatility smile shows a negative skew typical of equity markets
- Black-Scholes assumptions do not fully capture market behavior

## How to run

Install dependencies:

```bash
pip install -r requirements.txt
