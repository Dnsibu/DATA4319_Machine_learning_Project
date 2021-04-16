# The  K-Means Clustering Algorithm

![](https://miro.medium.com/max/1200/1*TmvsQ4XaOxeb-TmKk1qgOw.png)

## What is K-Means Clustering?

In the k-means clustering algorithm, we group the data into k groups or clusters such that
all the data points in the same cluster are as similar to each other as possible. The data points that 
aren't in that cluster are visibly different than those points.

To calculate the similarity between data points,  we use distances measures such as the euclidean distance. Each group has a centroid (central point), and they are thought of as the representative of the group.

## How does  K-Means Clustering work?
1. Calculate the Euclidean distance from each feature vector to each centroid.

3. Assign to each feature vector the centroid that is closest.
4. We next update the centroids in  by the following equation:

5. Repeat previous steps until convergence is reached.
