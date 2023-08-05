# Crypto-Clustering

## Overview
This project examined price changing data of 41 cryptocurrencies.

![Cryptocurrency price changes](/images/standardizedData.png)


With the unsuperviesed learning model, K-means algorithm, the project clustered the data points of the standardized data and the standardized data that has been processed by PCA with three features. The number of clusters are obtained through the elbow method.

| original data | PCA | elbow curves |
|-------------|-------------|-------------|
| 7 features | 3 features | ![Elbow curves comparison](/images/elbowCurvesComparison.png) |


## Analysis of the necessity for this datase
For this dataset, using fewer features (3 instead of 7) with the same methods for clustering the data (K-Means) doesn't make a significant change in the final clusters, as shown with the same clustering results they give.
| Clustering with and witout PCA |
|---------|
| ![Data clusteriing](/images/clusteringComparison.png) |

  


## Technologies utilized
* KMeans
* Principal Component Analysis (PCA)
* [kneed](https://github.com/arvkevi/kneed)

