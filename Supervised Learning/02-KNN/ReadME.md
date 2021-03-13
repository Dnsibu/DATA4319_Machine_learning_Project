# The K-Nearest Neighbors Algorithm
![](https://www.coryjmaklin.com/media/machine-learning-algorithms-part-6-k-nearest-neighbors-in-python-1.png)

## What is k-NN?

k-Nearest neighbors is one of the simplest supervised machine learning algortithm there is. It is sometimes called the lazy algortithm because of how so simple it is. While it's mostly used for solving classification problems, this algorithm can also be used to solve regression and search (reccomendations) problems. It makes no mathematical assumptions, and it doesn’t require any sort of heavy machinery. 

The only things it requires are:

+	Some notion of distance
+	An assumption that points that are close to one another are similar

Pros:
+ 1. Can be used for classification, regression, and search problems
+ 2. Simple and easy to implement
+ 3. No optimization of parameters
    
Cons:
+ 1. slow
+ 2. Sensitive to high dimension feature vectors and high volume of data

## How does k-NN work?

k-NN predicts a class (discrete value)  when it is being used for classification. The 3 key functions for this algortihtm are:

+ 1. Calculating the distance between any two points
+ 2. Find k, the number of nearest neighbors, based on the distances
+ 3. Majority vote on a class labels based on the nearest neighbor list

## The Distance
The most popular distance measure used for this algorithm is the Euclidean Distance. It is calculated as the square root of the sum of the squared differences between a new point and an existing point across all input attributes.
![](https://i.stack.imgur.com/RtnTY.jpg)
