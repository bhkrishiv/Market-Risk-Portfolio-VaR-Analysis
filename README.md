# Market Risk Modelling & Portfolio VaR Analysis

## Project Overview

An Excel-based project to measure market risk in an equally weighted portfolio of five Indian equities: HDFC Bank, Reliance Industries, Infosys, ITC and ICICI Bank.

The project focuses on estimating potential portfolio losses using different Value at Risk (VaR) methodologies and evaluating their performance through backtesting.

## Methodology

**1. Historical Simulation VaR**
- Estimated VaR using historical portfolio returns.
- Calculated at 95% and 99% confidence levels.

**2. Parametric VaR**
- Used the mean and standard deviation of portfolio returns.
- Assumed a normal distribution of returns.

**3. Monte Carlo VaR**
- Generated 10,000 simulated portfolio returns.
- Estimated VaR using the simulated loss distribution.

**4. Backtesting**
- Used 2023–2025 data for model estimation.
- Tested the forecasts against out-of-sample returns from January to September 2026.
- Compared actual breach rates with expected breach rates.

**5. Distribution Analysis and Stress Testing**
- Examined return distribution using a histogram and Q-Q plot.
- Analysed skewness and kurtosis.
- Tested the portfolio under different market scenarios.

## Key Findings

- Compared portfolio VaR estimates across three methodologies.
- Historical VaR at 95% confidence recorded a higher-than-expected breach rate during out-of-sample testing.
- Parametric and Monte Carlo VaR produced similar estimates due to their common normality assumption.
- Examined the limitations of normal-distribution-based risk models.

## Tools Used

- Microsoft Excel 2021
- Statistical analysis
- Financial risk modelling

## Assumptions and Limitations

- Portfolio weights are assumed to remain constant at 20% for each stock.
- Parametric and Monte Carlo models assume normally distributed returns.
- Historical VaR depends on the selected estimation period.
- Historical closing prices may not fully account for all corporate actions.
- Backtesting is based on a limited out-of-sample period.

## Project File

The Excel workbook contains the portfolio calculations, three VaR models, distribution analysis, stress testing and backtesting.
