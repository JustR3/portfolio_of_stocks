# Stock Portfolio Analysis

A comprehensive Python-based stock portfolio analysis tool that combines multiple forecasting models, technical analysis, and portfolio optimization techniques.

## Features

- Historical stock data retrieval using yfinance
- Time series decomposition using Facebook Prophet
- Multiple forecasting models:
  - ARIMA
  - Prophet
  - XGBoost
- Portfolio optimization using the Efficient Frontier
- Risk metrics calculation:
  - Volatility
  - Sharpe Ratio
  - Sortino Ratio
  - Maximum Drawdown
- Correlation analysis and visualization

## Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/portfolio_of_stocks.git
cd portfolio_of_stocks
```

2. Create a virtual environment (recommended)

Using venv:
```bash
python -m venv venv
source venv/bin/activate  # On Unix/macOS
venv\Scripts\activate     # On Windows
```

OR using conda:
```bash
conda create -n stock_analysis python=3.9
conda activate stock_analysis
```

3. Install the required packages
```bash
pip install -r requirements.txt
```

## Usage

The main analysis is contained in `analysis.ipynb`. The notebook includes:

1. Data fetching and preprocessing
2. Stock decomposition into trend, seasonality, and noise
3. Stock analysis with various metrics
4. Model evaluation and comparison
5. Trading strategy evaluation
6. Multi-stock analysis and portfolio optimization
7. Visualization of results

## Example Output

The analysis provides:
- Individual stock metrics
- Correlation matrix
- Optimal portfolio weights
- Visual representations of all analyses

## Note

The default analysis uses a 10-year period for the following tech stocks:
- AAPL (Apple)
- MSFT (Microsoft)
- GOOGL (Google)
- AMZN (Amazon)
- META (Meta)
- TSLA (Tesla)
- NVDA (NVIDIA)
- PLTR (Palantir)
- ADBE (Adobe)
- INTC (Intel)

You can modify the `TICKERS` and `PERIOD` variables to analyze different stocks and timeframes.
