# Apple DCF Valuation Model (Python)

A simplified discounted cash flow (DCF) model built in Python to estimate 
Apple's (AAPL) enterprise value, using real financial data pulled live 
via the `yfinance` library.

## What this project does
- Pulls Apple's real historical revenue directly from Yahoo Finance
- Calculates historical revenue growth and forecasts 5 years forward
- Projects free cash flow and discounts it to present value
- Adds a terminal value using the Gordon Growth Model
- Wraps the full pipeline into a reusable function that works for any public company ticker
- Runs sensitivity analysis across discount rate and FCF margin assumptions
- Visualizes results with a sensitivity heatmap

## Tools used
Python, pandas, matplotlib, yfinance, numpy

## Key takeaway
This project demonstrates core valuation mechanics (forecasting, discounting, 
terminal value, sensitivity analysis) — the same logic used in professional 
DCF models, simplified for learning purposes with real market data.

## Example output
Estimated Apple enterprise value under base-case assumptions (9% discount rate, 
25% FCF margin): ~$1,597B (before further refinement to margins, discount rate, 
and balance sheet adjustments).
