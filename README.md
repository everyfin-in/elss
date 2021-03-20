# Analysis of Tax saving Equity Linked Savings Schemes in India using PYTHON
Analysis of Tax Saving Equity Linked Savings Schemes (ELSS Mutual funds) in India using Python.

There are over 40 different ELSS mutual funds in India. The objective of this exercise is to use historic returns data and current portfolio composition data to identify the best funds to invest in. We distill down to 5 different funds from the initial list and then use PCA (principal components analysis) to understand similarities between these funds.

The data for the analysis is attached as an excel file. It needs to be in the same folder as the ipynb file.
risk_toolkit.py consists of functions that calculate simple risk ratios based on historic returns.

The code requires selenium and chromedriver to be installed and located in the PATH.

The code scraps data from valueresearchonline and this can take sometime.
