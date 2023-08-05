# Crypto-Clustering

## Overview
This project examined price changing data of 41 cryptocurrencies.

![Cryptocurrency price changes](/images/standardizedData.png)

### Clustering
With the unsuperviesed learning model, K-means algorithm, the project compared the clustering of the data points using all of the features with the clustering using only 3 features that are determined by PCA. 

The number of clusters are obtained through the elbow method.

| original data | PCA |
|-------------|-------------|
| 7 features | 3 features | 
| ![](/images/Kmeans.png) | ![](/images/pcaKmeans.png) |

| elbow curves |
|-------------|
| ![Elbow curves comparison](/images/elbowCurvesComparison.png) |

## Analysis of the necessity of PCA for this datase
For this dataset, using fewer features (3 instead of 7) with the same methods for clustering the data (K-Means) doesn't make a significant change in the final clusters, as shown with the same clustering results they give. This is possibly due to the small size of the dataset.
| Clustering both with and witout PCA |
|---------|
| ![Data clusteriing](/images/clusteringComparison.png) |

## Technologies utilized
* KMeans
* Principal Component Analysis (PCA)
* [kneed](https://github.com/arvkevi/kneed)

