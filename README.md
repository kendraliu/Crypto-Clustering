# Crypto-Clustering

## Overview
This project examined price changing data of 41 cryptocurrencies.

![Cryptocurrency price changes](/images/standardizedData.png)

With the unsuperviesed learning model, K-means algorithm, the project clustered the data points of the standardized data and the standardized data that has been processed by PCA with three features. The number of clusters are obtained through the elbow method.

![Elbow curves comparison](/images/elbowCurvesComparison.png)
![PCA components](/images/pcaComponents.png)
![Data clusteriing](/images/clusteringComparison.png)

## Technologies utilized
* KMeans
* Principal Component Analysis (PCA)
* [kneed](https://github.com/arvkevi/kneed)

