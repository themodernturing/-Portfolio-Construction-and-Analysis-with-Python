# Risk Analysis Toolkit

This project provides a set of tools and a Jupyter Notebook to analyze financial return series and assess downside risk.

## Contents

- **`edhec_risk_kit_106.py`**  
  A utility module with functions for risk analysis, including:
  - Drawdown computation
  - Skewness and kurtosis
  - Normality tests (Jarque-Bera)
  - Downside risk measures:
    - SemiDeviation
    - Value at Risk (VaR)
    - Conditional VaR (CVaR)
    - Modified VaR (Cornish-Fisher expansion)
  - Return loaders for Fama-French and EDHEC Hedge Fund indices

- **`Risk_Analysis_Notebook.ipynb`**  
  A Jupyter Notebook that demonstrates how to use the utility functions to:
  - Analyze and visualize drawdowns
  - Compare return distributions
  - Calculate downside risk measures

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/themodernturing/your-repo.git
   cd your-repo

