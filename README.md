# INFO6205_PSA_Final_Project

## K-means Algorithm

K-means clustering is a simple and popular type of unsupervised machine learning algorithm, which is used on unlabeled data. The goal of this algorithm is toﬁnd groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups according to provided features similarity. Algorithm steps for K-means given as following.

Randomly pick K observations and set them as initial cluster centers
Iterate until cluster assignments stop changing:
For each of the K clusters, compute the cluster centroid. The kth clustercentroid is the vector of the p feature means for the observations in the kth cluster.
Assign each observation to the cluster whose centroid is closest (where closest is deﬁned using Euclidean distance).
When N is number of samples and K is number of clusters, K-means algorithm try to minimize objective function which given as following.

![Objective Function](https://user-images.githubusercontent.com/45906647/90062451-613ef880-dcf0-11ea-9f19-6a3f12496b28.png)


### Here's an example visualization:
[gifKmeans](https://github.com/stratzilla/k-means-clustering/blob/master/images/perfect.gif)


