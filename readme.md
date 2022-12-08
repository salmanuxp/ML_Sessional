# Machine Learning Sessional Project

## Prediction of Error Classification in Grouping fire according to SOP of Bangladesh Army

## Dataset 

Dataset originally taken from image captured in firing range. The bullet holes were detected using Resnet 50, a deep neural network algorithm. After fine tuning, the bullet positions were normalized to 0,1 co-ordinate.

Initial dataset consists of locations of 5 points. And one target variable as 'Error Classification'.

## Dataset conversion

A Notebook file converts the intial dataset into a modified dataset which applies 'pdist' function to calculate all euclidean distances as a sum from each point.

This modified dataset had been further used to set up learning algorithms.


## Algorithms used

1. Random Forest, Fine tuned after hyperparameter optimization
2. Decision Tree
3. KNN - K Nearest Neighbour
4. Neural Network



