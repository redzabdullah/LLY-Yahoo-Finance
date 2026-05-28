# LLY Yahoo Finance Daily Price Panel

This repository contains a Google Colab notebook that retrieves daily historical stock price data for Eli Lilly and Company (`LLY`) from Yahoo Finance and transforms it into a firm-date panel for financial analysis.

## Overview

The notebook uses Python to download daily stock price data beginning from 2020-01-01 through the latest available trading date. The data are cleaned, transformed, and exported as a CSV file.

## Variables

The final dataset includes:

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

## Tools Used

- Python
- Google Colab
- pandas
- numpy
- yfinance
- Yahoo Finance

## Output

The main output file is:

```text
lly_daily_panel_2020_latest.csv
