
# Predicting Car Prices Using K-Nearest Neighbors Algorithm

This project is a part of the guided project from Dataquest. I also develop and do further data analysis on my own using different techniques to split a dataset into training and test sets, and applying k-nearest neighbors algorithm with different k values to predict the car prices. The dataset used in this project is from https://archive.ics.uci.edu/ml/datasets/automobile.

The outlines of this notebook presentation is as follows:

 - Data Exploration
 - Data Cleaning
 - Splitting Data Method 1: shuffle the dataset before splitting using numpy.random.permutation 
    - Univariate Model: using one feature in our model. 
    - Multivariate Model: using multiple features in each model and compare the results by calculating the root-mean-squre error (RMSE).
    - Hyperparameter Tuning: varying k values in k-nearest neighbors and compare the results using the RMSEs of individual models.
 - Splitting Data Method 2: K-Fold Validation
comparing the results from this part to Method 1's solutions where we split the shuffled dataset into training and test sets.
