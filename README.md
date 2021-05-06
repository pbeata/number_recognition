# Handwritten Number Recognition

_In this project, we perform an optimization of a deep neural network for a handwritten number recognition classification task using the MNIST data set._

* Built deep neural networks to perform image recognition and classification of handwritten digits from the MNIST data set.
* The MNIST data set contains 70,000 handwritten digits split into training and testing sets: for data preprocessing, we generate a third set for validation using a subset (10%) of the training data
* Each image in the set is comprised of 28x28 grayscale pixels ranging in value from 0 to 255: as part of the data preprocessing, we scale these pixels value to the range of [0, 1] as well
* For training the deep neural net, we vary the width and depth of the model in search of an optimal solution: tested hidden layers sizes (width) of 8, 16, 32, 64, 128, and 256 and the number of layers in the NN (depth) used were 2, 4, and 8
* Using four layers in the NN with a size (width) of 256 nodes, we achieve an classification accuracy of 98.1%; meaning, we correctly classified 9,813 handwritten images out of the 10,000 total in the testing data subset
