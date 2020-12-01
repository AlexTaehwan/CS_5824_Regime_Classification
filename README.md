# CS_5824_Regime_Classification
CS 5824 (Advanced Machine Learning) Final Project

## Using smart beta factors as input for Random Forest time series classification
"Machine Learning in finance is like using an image classifier to identify a zebra, and the zebra is constantly changing colors." - Michael Kearns

Herein, we aim to identify periods where the zebra's colors are consistant, using smart beta factors as input to time series classification methods.

## Datasets (2010/7/1 - 2020/7/1, 10 years long)
- VIX
- Oil
- Dollar Index
- credit spread
- monetary base
- period spread
- Year_1_bond
- Year_2_bond
- Year_10_bond

## Clustering Algorithm(s) used
- KernelKMeans
- DTW TS KMeans
- SoftDTW TS KMeans

## Classification Algorithm(s) used
- XGBoost
