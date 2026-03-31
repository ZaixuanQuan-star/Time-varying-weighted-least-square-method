Forecasting Stock Returns: A Time-Varying Robust Weighted Least Squares (TRWLS) Approach
![alt text](https://img.shields.io/badge/python-3.8%2B-blue)

![alt text](https://img.shields.io/badge/license-MIT-green)
This repository provides a Python implementation/reproduction of the paper: "Forecasting stock returns: A time-varying robust weighted least squares approach".
Original Paper Link: Journal of Management Science and Engineering (2021),https://jmsc.tju.edu.cn/jmsc/article/abstract/202102150275


Project Overview

Predicting stock returns is challenging due to parameter instability and market noise. This project implements the TRWLS (Time-varying Robust Weighted Least Squares) framework to forecast the S&P 500 index excess returns.
The TRWLS method innovatively combines:
Time-dependent weights: To capture parameter instability over time.
Robustness weights: To mitigate the influence of outliers and market noise.
Machine Learning: Automated hyperparameter selection for optimal forecasting performance.


Key Features

Time-Varying Dynamics: Implements kernel-based weighting (e.g., Gaussian/Exponential) to prioritize recent information.
Robust Estimation: Incorporates robust loss functions to handle the "fat-tail" distribution of financial data.
Hyperparameter Tuning: A grid search or ML-based validation strategy to select optimal bandwidth and robustness parameters.
Backtesting Suite: Includes both Statistical Evaluation (R-squared, MSPE) and Economic Evaluation (Certainty Equivalent Return, Sharpe Ratio).
Comparison Baselines: Support for OLS and standard WLS models for performance benchmarking.

If you find this reproduction helpful, please cite the original paper:
Zhou, Z., et al. (2021). Forecasting stock returns: A time-varying robust weighted least squares approach. Journal of Management Science and Engineering.
