---
title: Clustering Algorithms
---
## Clustering Algorithms

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/machine-learning/clustering-algorithms/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
A loose definition of clustering could be “the process of organizing objects into groups whose members are similar in some way”. A cluster is therefore a collection of objects which are similar between them and are dissimilar to the objects belonging to other clusters.

So, the goal of clustering is to determine the intrinsic grouping in a set of unlabeled data. But how to decide what constitutes a good clustering? It can be shown that there is no absolute “best” criterion which would be independent of the final aim of the clustering. Consequently, it is the user which must supply this criterion, in such a way that the result of the clustering will suit their needs.

For instance, we could be interested in finding representatives for homogeneous groups (data reduction), in finding “natural clusters” and describe their unknown properties (“natural” data types), in finding useful and suitable groupings (“useful” data classes) or in finding unusual data objects (outlier detection).

The typical kinds of clustering algorithms are :
1. Connectivity-based clustering 
2. Centroid-based clustering
3. Distribution-based clustering
4. Density-based clustering


##### Connectivity-based clustering or hierarchical clustering
This is based on the core idea of objects being more related to nearby objects than to objects farther away. These algorithms connect "objects" to form "clusters" based on their distance. Hence, a cluster can be described largely by the maximum distance needed to connect parts of the cluster.

##### Centroid-based clustering
In centroid-based clustering, clusters are represented by a central vector, which may not necessarily be a member of the data set. When the number of clusters is fixed to k, k-means clustering gives a formal definition as an optimization problem: find the k cluster centers and assign the objects to the nearest cluster center, such that the squared distances from the cluster are minimized.

##### Distribution-based clustering
The clustering model most closely related to statistics is based on distribution models. Clusters can then easily be defined as objects belonging most likely to the same distribution. A convenient property of this approach is that this closely resembles the way artificial data sets are generated: by sampling random objects from a distribution.

##### Density-based clustering
In density-based clustering, clusters are defined as areas of higher density than the remainder of the data set. Objects in these sparse areas - that are required to separate clusters - are usually considered to be noise and border points.


#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
..* <https://en.wikipedia.org/wiki/Cluster_analysis#Algorithms>
..* <https://web.stanford.edu/class/cs345a/slides/12-clustering.pdf>
