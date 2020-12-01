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

We ended up choosing KernelKMeans as our clustering algorithm since it gives us the most well distributed classification results.
## Classification Algorithm(s) used
- XGBoost

## Code (written in python, colab)
Code consists of 4 parts: Data Collection, Clustering, XGBoost, Main
1. Import 11 csv files (cboe_vix.csv, corporate_bond_yeild.xls, dollar_index.csv, Golbal_Alignment_Kernel_Labels.csv, monetary_base.csv, oil.csv, TIPS.csv, treasury_bond.csv, Year_1.csv, Year_2.csv, Year_10.csv)
2. Run Clustering (in Main)
3. Run XGBoost (in Main)
