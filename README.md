# K Nearest Neighbors Algorithm
The aim of the project is to create a model that directly predicts a class for a new data point based on the given features. Here I tried to used the ML algorithms KNN to create a model that directly predicts a class for a new data point.
This project demostrate how to select optimize K value to build the KNN model for most accurate prediction. 

   The dataset is classified dataset from a company! The column names of the dataset are hidden due to security issues. The features and the target classes are provided.

# Standardize the Variables
In order to use KNN algorithms we need standardize the features because the KNN classifier predicts the class of a given test observation by identifying the nearest observations. Therefore, the scale of the variables effects the prediction quality and processing time. Therefore, variables that are on a large scale will have a much larger effect on the KNN classifier than variables that are on a small scale. To scale down the variables I used StandardScaler from sklearn lib.

Model
The goal is to build a model to predict wheter new data point will be TARGET CLASS. First I start with k value as one. Then I analysied the error rate setting  k value from 1 to 40 and found that after k value  23 the  error rate just tends to vary around 0.06-0.05 . Therefore, I train the model with k=23 and evaluate the model by checking the classification reports . I compare the model with k value as 1 and observe significant improvements. 
