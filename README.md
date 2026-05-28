# LLY-Yahoo-Finance
# Yahoo Finance LLY Daily Panel

This repository contains a Google Colab notebook that retrieves daily historical stock price data for Eli Lilly and Company (`LLY`) from Yahoo Finance.

## Dataset

The notebook creates a firm-date panel from 2020-01-01 to the latest available trading date.

The exported CSV includes:

- ticker
- date
- open
- high
- low
- close
- adj_close
- volume
- dividends
- stock_splits
- daily_return
- log_return
- dollar_volume
- year
- month
- quarter

## Tools used

- Python
- pandas
- numpy
- yfinance
- Google Colab
- Yahoo Finance

## Output

The main output file is:

```text
lly_daily_panel_2020_latest.csv
