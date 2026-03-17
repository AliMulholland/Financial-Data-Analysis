**Financial Market Data Analysis**

This project analyses 10 years of stock market data (2015–2024) for 70 large companies using Python. The goal is to explore key financial characteristics such as returns, volatility, correlations, and market risk using both statistical analysis and machine learning techniques.


**Repository Structure**

Each notebook corresponds to a section of the analysis presented in the report:

> Financial Data Analysis.pdf – Full report summarising the analysis and findings

> data_annual_return_volatility.ipynb – Calculation of annual returns and volatility

> risk_correlations_drawdowns.ipynb – Risk analysis including correlations and drawdowns

> distribution.ipynb – Analysis of return distributions and fat tails

> Machinelearning.ipynb – K-Means clustering of stocks based on financial features

**Overview**

The dataset was obtained using the Yahoo Finance API (yfinance) and includes daily market data such as:

> Open price

> Close price

> Daily high and low

> Trading volume

Companies with insufficient historical data were removed to ensure consistency across the dataset.

**Analysis Performed**

The project explores several key financial concepts:

> Stock Prices and Returns

> Daily returns calculated from closing prices

> Cumulative returns used to identify top performing stocks over the 10-year period

> Risk and Volatility

> Annualised return vs volatility scatter plots

> Identification of risk-return characteristics across companies

> Correlation Analysis

> Correlation heatmaps of daily returns

> Comparison of correlations during stable markets vs crisis periods (e.g., COVID-19 in 2020)

> Rolling Volatility

> 252-day rolling volatility analysis

> Comparison of volatility behaviour across industries

> Drawdown Analysis

> Maximum drawdowns calculated for each stock

> Identification of the largest historical losses

> Return Distributions

> Log return distributions analysed

> Comparison with normal distributions

> Evidence of fat-tailed behaviour in financial markets

> Machine Learning (Clustering)

> K-Means clustering applied to group stocks with similar characteristics

**Features used:**

> Mean return

> Volatility

> Maximum drawdown

> Elbow method used to determine the optimal number of clusters

> Tools Used

> Python

> Pandas

> NumPy

> Matplotlib

> Seaborn

> Scikit-learn

Author: Ali Mulholland
Physics BSc @ The Univeristy of Edinburgh



yfinance

Key Insight

Financial return distributions show fat tails, meaning extreme market movements occur more frequently than predicted by a normal distribution. Additionally, correlations between stocks increase significantly during market crises.
