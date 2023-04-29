# Perceptron


This code implements the Perceptron Learning Algorithm (PLA) to learn a linear decision boundary between two classes of data points in 2-dimensional space.

The training data consists of 6 data points, each with 2 features (x1 and x2) and a binary class label (1 or -1). The initial weight vector w is set to [1, 1].

The PLA algorithm then iteratively updates the weight vector based on the misclassification of each data point until all points are correctly classified. In each iteration, the algorithm checks if the current data point is correctly classified by computing the dot product of the weight vector and the data point's feature vector. If the sign of the product does not match the data point's class label, the weight vector is updated by adding the product of the class label and the feature vector to the current weight vector. The number of updates (i.e., iterations) required for the algorithm to converge is printed at the end.

Finally, a plot is generated to visualize the data points and the learned decision boundary. The x1 and x2 values are generated using numpy and used to plot a line representing the decision boundary. The data points are then plotted using matplotlib, with green and red indicating the positive and negative classes, respectively.
