# Softwere-Project
# K-means and Spectral Clustering Algorithms Implementation
This repository contains implementations of the K-means clustering algorithm and the spectral clustering algorithm using both Python and C. The implementations of the K-means algorithm utilize C modules and the C API, providing efficient computation. The spectral clustering implementations are available in both Python and C as well.

## K-means Algorithm
The K-means algorithm is a popular unsupervised ML algorithm used for clustering analysis. It aims to partition a dataset into K distinct clusters based on similarity measures. The algorithm works by iteratively assigning data points to the nearest cluster centroid and updating the centroids based on the newly assigned points. This process continues until convergence, resulting in clusters with minimized within-cluster variance.

## Spectral Clustering Algorithm
The spectral clustering algorithm is another approach to clustering data points. It utilizes the spectrum (eigenvalues) of a similarity matrix to perform clustering. The algorithm involves constructing an affinity matrix to capture pairwise similarities between data points and then computing the eigenvectors corresponding to the largest eigenvalues of the matrix. These eigenvectors are used to embed the data points into a lower-dimensional space, where traditional clustering techniques (e.g., K-means) can be applied.
