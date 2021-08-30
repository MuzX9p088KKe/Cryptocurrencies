# Cryptocurrencies

## Overview

The purpose of this project was to cluster different types of cryptocurrencies using unsupervised machine learning.
In order to do so, [a CSV file was sourced from CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist) and its data was cleaned up.

First, the data was pre-processed for PCA. The data dimensions were then reduced using PCA before the cryptocurrencies were finally clustered using K-means.

## Results

### 3D Scatter Plot

After using PCA and deciding on 3 principal components, the following 3D scatter plot was produced using Plotly:

[3D Scatter Plot]

The interactive scatter plot is available [in the jupyter notebook].

### Tradable Cryptocurrencies table

A table was created using hvplot. It includes all the tradable cryptocurrencies and their data.

[Table preview]

The full table is accessible [in the jupyter notebook]() as well.

### 2D Scatter Plot

Lastly, hvplot was used to produce a scatter plot showing the cryptocurrencies clusters distributed by mined coins and total supply.

[2D scatter plot]
