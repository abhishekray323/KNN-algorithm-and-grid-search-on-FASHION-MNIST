# KNN-algorithm-and-grid-search-on-FASHION-MNIST
## Introduction
In this model we have used KNN algorithm. K-Nearest Neighbors is one of the most basic yet essential classification algorithms in Machine Learning. It belongs to the supervised learning domain and finds intense application in pattern recognition, data mining and intrusion detection. 

## Methodology
In this project we have made a grid hyper parameter such as k and distance metric for determining the optimal combination of hyper parameters. The dataset was divided in two sets that are training set and test set. In KNN the training set is completely used for prediction of the labels for the test set. For a new data point distance from all data points in training set are calculated and then sorted in ascending order then according to the hypothesized value of K, top K data points are considered for labeling.  This procedure was followed for different values of K along with different distance metric. We finally display the best combination of value of K and distance metric.   

## Results 
<img src="https://github.com/abhishekray323/KNN-algorithm-and-grid-search-on-FASHION-MNIST/blob/master/result.png" >

#### Figure 1 :Accuracy Score                                                                                                                                                          
Here blue color line refers to distance calculated through Euclidean Method.
Here Red color Line refers to distance calculated through Manhattan Method.
Here Green Color Line refers to distance calculated through Chebyshev Method. 

## Conclusion 
So for all methods we get maximum accuracy for K=1.<br>
Max Accuracy Using Euclidean Distance is 0.8491666666666666.<br>
Max Accuracy Using Manhattan Distance is 0.8505833333333334.<br>
Max Accuracy Using Chebyshev Distance is 0.6374166666666666.<br>
Best Model: Metric = Manhattan and K=1. 

## Sources 
https://www.geeksforgeeks.org/k-nearest-neighbours/

https://www.researchgate.net/figure/The-flowchart-of-K-nearest-neighbor-classifier-procedure_fig2_237080861

https://www.kaggle.com/zalando-research/fashionmnist
