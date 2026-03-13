Here's a clean README for the project:

---

# 📈 Bank Stock Finance Analysis (2006–2016)

## Overview
An exploratory data analysis (EDA) project examining the stock performance of major U.S. banks throughout the 2008 financial crisis and into early 2016. This project is intended for **practice with pandas and data visualization** — not as financial advice.

## Banks Analyzed
- Bank of America (BAC)
- CitiGroup (C)
- Goldman Sachs (GS)
- JPMorgan Chase (JPM)
- Morgan Stanley (MS)
- Wells Fargo (WFC)

## Dependencies
```
pandas, pandas_datareader, numpy, matplotlib, seaborn, plotly, cufflinks, datetime
```

## Key Analyses
- **Daily returns** — calculated via `pct_change()` on closing prices
- **Risk assessment** — standard deviation of returns across the full period and for 2015
- **Best/worst single-day returns** — notable events include the 2009 inauguration day selloff and Citigroup's 2011 stock split
- **Moving averages** — 30-day rolling average for BAC during 2008
- **Correlation heatmap** — close price correlations across all six banks
- **Technical analysis** — candlestick charts, Simple Moving Averages (SMA), and Bollinger Bands via cufflinks
