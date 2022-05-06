# K Nearest Neighbors Algorithm
The dataset is classified dataset from a company! The column names of the dataset are hidden due to security issues. The features and the target classes are provided.

The aim of the project is to create a model that directly predicts a class for a new data point based on the given features. Here I tried to used the ML algorithms KNN to create a model that directly predicts a class for a new data point.

Standardize the Variables
In order to use KNN algorithms we need standardize the features because the KNN classifier predicts the class of a given test observation by identifying the nearest observations. Therefore, the scale of the variables effects the prediction quality and processing time. Therefore, variables that are on a large scale will have a much larger effect on the KNN classifier than variables that are on a small scale. To scale down the variables I used StandardScaler from sklearn lib.
