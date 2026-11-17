# Candlestick pattern analysis

This notebook detects engulfing and star candlestick patterns in historical Tesla prices, combines them into reversal signals, and visualizes the flagged observations with Plotly.

## Run the notebook

From the repository root, create and activate a Python virtual environment, then install the notebook dependencies.

```sh
python -m venv .venv
. .venv/bin/activate
python -m pip install jupyterlab 'yfinance>=0.2.54' pandas numpy plotly
python -m jupyterlab
```

Open [823 Project Candle Sticks Pattern Final Version.ipynb](823%20Project%20Candle%20Sticks%20Pattern%20Final%20Version.ipynb) and select the virtual environment's Python kernel. Run the cells in order.

## Data

The notebook downloads daily TSLA prices from Yahoo Finance. The date window starts January 1, 2015 and ends before July 16, 2022. An internet connection is required.

The plots mark rule-based patterns. The project does not simulate transaction costs or estimate strategy returns.
