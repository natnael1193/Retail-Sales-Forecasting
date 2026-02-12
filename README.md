# Retail Sales Forecasting for Multi-Store Retailer

## Project Overview

This project develops a machine learning-based demand forecasting system
to predict daily store-level sales in a retail environment.

## Business Objective

Improve inventory planning accuracy and reduce stockouts/overstock by
reducing forecast error.

## Dataset

-   Date
-   Store Number
-   Product Family
-   Sales (Target)
-   On Promotion

## Methodology

-   Aggregated sales at store-day level
-   Engineered time-based features
-   Created lag features (1, 7, 30 days)
-   Rolling averages (7-day, 30-day)
-   Time-based train/test split

## Models

-   Naive Baseline
-   Random Forest
-   XGBoost

## Results

-   Baseline RMSE: 5348
-   Random Forest RMSE: 2485
-   XGBoost RMSE: 2278
-   MAPE: 9.75%
-   57% RMSE reduction vs baseline

## Business Impact

Sub-10% MAPE demonstrates production-ready retail forecasting capability
and supports improved demand planning.

## Technologies

Python, Pandas, Scikit-learn, XGBoost, Matplotlib

## Future Improvements

-   LSTM deep learning models
-   Hierarchical forecasting
-   Inventory optimization simulation
