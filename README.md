**Class: CSC 4850 - Machine Learning with Dr. Banda Juan**

Student name: Mike Doan - mdoan4 - 002551968

Analysing the UCI ML Wine recognition datasets using basic machine learning algorithmns (perceptron, decision tree, logistic regression) through use of the sklearn library

https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data 

Summary of findings from a single split of data with random seed '1234':
 * The Perceptron model performs quite poorly on a simplified version of the data set with only 2 classes (class_0, class_1), with an accuracy, recall and precision of around 75% on the training set, and around 67% on the testing set
 * The decision tree model performs well on the data set, with perfect performance metrics on the training set and 93% accuracy, weighted recall and precision on the testing set
*  The logistic regression model performs the best out of the tested models, with roughly 98% accuracy on the training set and 95% accuracy, weighted recall and precision on the testing set

Libraries used:
* numpy
* pandas
* sklearn
* matplotlib
* sesborn
