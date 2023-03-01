What is Feature Scaling?
Feature scaling is a data preprocessing technique used in machine learning to rescale the features or variables in a dataset. Feature scaling is necessary because different features in a dataset may have different scales or units of measurement, which can affect the performance of some machine learning algorithms.

The most common methods of feature scaling are normalization and standardization.

Normalization involves rescaling the features so that they have values between 0 and 1. This is done by subtracting the minimum value of the feature and dividing by the range (i.e., the difference between the maximum and minimum values). Normalization is useful when the distribution of the feature values is not Gaussian or when the algorithm used for modeling requires the features to be in a similar range.

Standardization involves rescaling the features so that they have a mean of zero and a standard deviation of one. This is done by subtracting the mean value of the feature and dividing by the standard deviation. Standardization is useful when the distribution of the feature values is Gaussian or when the algorithm used for modeling requires the features to have a mean of zero and a standard deviation of one.

Feature scaling helps to improve the performance of machine learning algorithms, particularly those that are sensitive to the scale of the input features, such as k-nearest neighbors, support vector machines, and neural networks.