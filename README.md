# K-nearest neighbour (KNN) 

K-nearest neighbour (KNN) is a supervised learning algorithm for classification and predictive modelling tasks. The name "K-nearest neighbour" reflects the algorithm's approach of classifying an output based on its proximity to other data points on a graph. 

Let's say you have a dataset with labelled points, some marked as blue and others as red. When you want to classify a new data point, KNN looks at its nearest neighbours in the graph. The "K" in KNN refers to the nearest neighbours considered. For example, if K is set to 5, the algorithm looks at the five closest points to the new data point.

The algorithm assigns a classification to the new data point based on most labels among the K nearest neighbours. For instance, if most of the nearest neighbours are blue points, the algorithm classifies the new point as belonging to the blue group.

Additionally, KNN can also be used for prediction tasks. Instead of assigning a class label, KNN can estimate the value of an unknown data point based on the average or median of its K nearest neighbours.
