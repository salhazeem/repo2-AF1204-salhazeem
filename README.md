# Sarah Alhazeem — Data Literacy Portfolio

Personal portfolio webpage for the AF1204 Data Literacy module.

**Live site:** https://salhazeem.github.io/repo2-AF1204-salhazeem

**Portfolio Notebook:** https://github.com/salhazeem/repo2-AF1204-salhazeem/blob/main/portfolio.ipynb

## Contents

| File | Description |
|------|-------------|
| `portfolio.ipynb` | Jupyter notebook that generates the portfolio HTML |
| `docs/index.html` | Generated portfolio webpage (served by GitHub Pages) |

## How to run

```bash
pip install jupyter yfinance pandas matplotlib numpy
python -m jupyterlab portfolio.ipynb
```

Run all cells — the notebook downloads real stock data, generates 4 charts, and writes `docs/index.html`.

## Projects

### Project 1 — Stock Price Analysis: Apple vs Tesla (2020–2024)
Real historical closing prices downloaded from Yahoo Finance using yfinance. Line chart comparing 5-year performance.

### Project 2 — Monthly Return Comparison (2023)
Month-by-month percentage returns calculated using pandas resample and pct_change. Shows volatility difference between Apple and Tesla.

### Project 3 — S&P 500 Sector Returns and Rolling Volatility (Interactive)
Two-view interactive chart. Sector returns for 2023 and 30-day rolling volatility calculated from real daily returns.

## Skills demonstrated

- Python programming (Weeks 1–4)
- Data visualisation with matplotlib and pandas (Weeks 1–4, 6)
- Real financial data retrieval using yfinance (self-exploration)
- Data wrangling: resampling, pct_change, rolling statistics (Weeks 6–9)
- Version control with GitHub (Week 10)
- Interactive web publishing via GitHub Pages (self-exploration)

## Data Sources

- Apple (AAPL) and Tesla (TSLA) stock prices: Yahoo Finance via [yfinance](https://pypi.org/project/yfinance/)
- S&P 500 sector returns (2023): Publicly reported annual index performance data
