# CRM & CM with Business Intelligence - Case Study
Analysis of S&P 500 stocks using weekly returns, beta, and RFM techniques to identify stock groups based on risk, return, and trading activity using Python clustering methods.

## How to run
1. Open `6BUIS017W_CRM_&_CM_With_BI.ipynb` in Google Colab and choose Runtime > Restart and run all.
2. The first cells install `yfinance` and `lxml`. 
3. To use the saved data instead of downloading, set `REFRESH = False`. The notebook then reads the `data/` folder.

## Key settings
- Study period: 2021-01-01 to 2025-01-01
- RFM observation date: 2024-12-31
- Constituent list retrieved from Wikipedia on 2026-11-24, prices from Yahoo Finance via yfinance
- Benchmark: ^GSPC
- 503 shares listed, 486 retained after validation (exclusion log in `outputs/`)
- 207 aligned Friday-ending weekly returns 

## Repository contents
- `6BUIS017W_CRM_&_CM_With_BI.ipynb`: Finalize CRM & CM with BI Python implementation (Tasks 1 to 3)
- `data/`: Add dataset files to the repository
- `outputs/`: Add output results for CRM & CM with BI
- `requirements.txt/`: Package versions

### Technologies
Python, Google Colab, Pandas, NumPy, yfinance, SciPy, scikit-learn, Matplotlib and Seaborn.

