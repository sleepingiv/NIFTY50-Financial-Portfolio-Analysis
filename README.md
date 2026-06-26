# NIFTY 50 Portfolio Risk Assessment & Technical Analysis

## Business Task

Advise a high-net-worth wealth management client on capital allocation between the Indian IT and Banking sectors. The objective is to optimize the portfolio for maximum return and minimum volatility (risk), while identifying technical entry points using historical moving averages.

## Tech Stack & Methodology

- Advanced Excel: Built an end-to-end quantitative financial model and executive dashboard.
- API Data Extraction: Bypassed manual CSV downloads by utilizing the GOOGLEFINANCE API to dynamically scrape 5 years (1,250+ trading days) of historical closing prices for 4 NIFTY 50 Blue-Chip stocks (TCS, INFY, HDFCBANK, ICICIBANK).
- Quantitative Math & Feature Engineering: Engineered custom formulas for Daily Return, Annualized Return, Annualized Volatility (STDEV.S * SQRT(252)), and 50-Day Simple Moving Averages (SMA).


## The BLUF (Key Insights)

- The Clear Winner (ICICI): The Risk vs. Return Matrix proves ICICI Bank dominates this cohort, posting the highest Average Annual Return (17%) while simultaneously maintaining the lowest Annualized Volatility (20%).
- IT Sector Underperformance: Over this specific 5-year macroeconomic window, the IT sector (TCS, INFOSYS) displayed negative annualized returns and higher relative volatility compared to the banking sector, making them unsuitable for a risk-averse profile at this time.
- Market Timing (Technical Analysis): By plotting the daily adjusted close against the 50-Day SMA, clear technical "Buy" signals emerge whenever the volatile daily price (blue) dips temporarily below the stable 50-day trendline (red).

## Strategic Recommendations

- Capital Allocation: Allocate the majority of the portfolio to ICICI Bank, as it mathematically proves to be the most efficient asset in the analyzed cohort.
- Entry Strategy: Utilize the programmed 50-Day Moving Average tracker to identify technical entry points (buy signals) to maximize long-term yield when entering the position.
Capital Allocation: Allocate the majority of the portfolio to ICICI Bank, as it mathematically proves to be the most efficient asset in the analyzed cohort.
Entry Strategy: Utilize the programmed 50-Day Moving Average tracker to identify technical entry points (buy signals) to maximize long-term yield when entering the position.
