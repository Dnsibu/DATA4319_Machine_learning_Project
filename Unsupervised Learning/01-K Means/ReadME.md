# The  K-Means Clustering Algorithm

![](https://miro.medium.com/max/1200/1*TmvsQ4XaOxeb-TmKk1qgOw.png)

## What is K-Means Clustering?

In the k-means clustering algorithm, we group the data into k groups or clusters such that
all the data points in the same cluster are as similar to each other as possible. The data points that 
aren't in that cluster are visibly different than those points. Points can only belong to one group.

To calculate the similarity between data points,  we use distances measures such as the euclidean distance. Each group has a centroid (central point), and they are thought of as the representative of the group.

## How does  K-Means Clustering work?
1. Choose the number of clusters k
2. Select k random points from the data as centroids. Calculate the Euclidean distance from each feature vector to each centroid.
![](https://camo.githubusercontent.com/11ef8ac96db197b5a396cfa43954a4d024d0e3d773cbd3f408075388e9967dea/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f52746e54592e6a7067)
3. Assign to each feature vector the centroid that is closest.
4. We next update the centroids in clusters.
5. Repeat previous steps 3-4 until convergence is reached ( no change to the centroids).
