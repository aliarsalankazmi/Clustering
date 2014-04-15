Cluster Analysis
============

This repository  contains all things related to Cluster Analysis. Files added hitherto can be viewed from the table presented below.

File name | Description | Credits
----------|-------------|---------
[Gap Statistic] (https://github.com/noobuseR/Clustering/blob/master/Gap%20Statistic) | The Gap Statistic is an algorithm that facilitates practitioners of Cluster Analysis to determine an appropriate number of clusters. Of course, this algorithm is only intended to be used after a user has performed clustering via any techniques that require the number of clusters to be stated explicitly {unlike those techniques that do not, e.g. Hierarchical Clustering}. It is also noteworthy that the Gap Statistic determines the appropriateness of a cluster number by taking into account the Total Within Cluster Sum of Squared Deviations. Specifically, it computes the Total Within Cluster Sum of Squares on the original data for a range of k clusters, and compares these with the Total Within Cluster Sum of Squares computed for the same range of k clusters on a set of reference, controlled datasets. As such, the Gap Statistic may only be used when the user agrees to and adopts the definition of appropriateness for the number of clusters as that involving reduction in the Within Cluster Sum of Squares. | This algorithm is credited to Tibshirani, Walther, and Hastie, from the paper ["Estimating the number of clusters in a data set via the gap statistic"] (http://www.stanford.edu/~hastie/Papers/gap.pdf). This particular implementation was inspired by Edwin Chen's elegant [implementation] (https://github.com/echen/gap-statistic) of the same algorithm.

