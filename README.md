# Task-2-predicting-optimum-number-of-clusters-for-iris-dataset

K-Means Clustering comes under Non-Hierarchial Clustering and it is a partition based clustering, the objective of K-means is simple: group similar data points together and discover underlying patterns.

K-means algorithm starts with randomly selected centroids, which are used as beginning points for every cluster, and then performs iterative calculations to optimize the positions of the centroid.
It's stops optimizing the position of the centroids in two cases: 
(1) when the centroids have stabilized(there is no change in their values because the clustering has been sucessful.) 
(2) when predefined number of iterations has been achieved.

In K-means clustering there is no dendogram we will upfront find the number of clusters using screeplot or elbow curve.

K-means clustering will perform well when we have large dataset and this algorithm will get influenced by noise and outliers in the dataset to overcome that we use K-medians or K-medoids.

So, in this task I used K-Means clustering with the help of the elbow curve found optimum number of clusters.
