# unit13-challenge


## Clustering Crypto

In this project, I will generate a report of the available cryptocurrencies on the trading market and how they can be grouped using classification.

The main task of this project include,
* Data Preprocessing: Prepare data for dimension reduction with PCA and clustering using K-Means.

* Reducing Data Dimensions Using PCA: Reduce data dimension using the PCA algorithm from sklearn.

* Clustering Cryptocurrencies Using K-Means: Predict clusters using the cryptocurrencies data using the KMeans algorithm from sklearn.

* Visualizing Results: Create some plots and data tables to present your results.


## imports/ installs

import requests
import pandas as pd
import matplotlib.pyplot as plt
import hvplot.pandas
from sklearn.preprocessing import StandardScaler, MinMaxScaler
from sklearn.decomposition import PCA
from sklearn.cluster import KMeans
from pathlib import Path

