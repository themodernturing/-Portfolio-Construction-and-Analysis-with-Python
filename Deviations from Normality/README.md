# Deviations from Normality

This project explores the statistical characteristics of financial return distributions, with a focus on their deviation from the normal distribution. Using hedge fund indices and Fama-French equity data, I performed a detailed analysis of skewness, kurtosis, and applied the Jarque-Bera test to assess normality.

## Objective

The goal of this analysis is to investigate whether common financial return series follow a normal distribution — a key assumption in many financial models — and to demonstrate proficiency in implementing and interpreting statistical measures using Python.

## Key Contributions

- **Custom Implementations**: Developed Python functions to calculate skewness and kurtosis from first principles to reinforce understanding of the underlying statistics.
- **Statistical Testing**: Applied the Jarque-Bera test to both synthetic and real-world financial data to assess normality assumptions.
- **Comparative Analysis**: Benchmarked custom implementations against `scipy.stats` to validate correctness and highlight differences in interpretation (e.g. excess kurtosis).
- **Use of Simulated Data**: Generated normally distributed return series using NumPy for baseline comparison.
- **Modular Design**: Encapsulated core functionality in a reusable Python module (`edhec_risk_kit_105.py`) to support clean, maintainable code.

## Data Sources

- **EDHEC Hedge Fund Indices**: Monthly returns across multiple hedge fund strategies.
- **Fama-French Market Equity (FFME)**: Returns for U.S. Small-Cap and Large-Cap portfolios.

## Technologies Used

- Python (Jupyter Notebook)
- `pandas` for data manipulation
- `numpy` for numerical operations
- `scipy.stats` for statistical functions and hypothesis testing

## Files

- `lab_105.ipynb`: Jupyter notebook containing the full analysis, code, and commentary.
- `edhec_risk_kit_105.py`: A supporting module with utility functions for statistical analysis.
- `README.md`: Project overview and methodology.

## Summary of Findings

- Many hedge fund strategies exhibit strong negative skewness and high kurtosis, deviating significantly from normality.
- The Jarque-Bera test confirms that most real-world return series in the dataset fail normality assumptions at the 1% significance level.
- Simulated normally-distributed returns serve as a useful control, validating the statistical tools and interpretations.

---

This project demonstrates my ability to combine quantitative finance knowledge with practical Python skills to investigate important assumptions in return modeling. It can be extended to include other statistical tests, more asset classes, or applied in risk modeling and portfolio construction workflows.

