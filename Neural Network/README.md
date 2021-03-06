- In "NeuralNetwork.ipynb" we build a class for an "input layer/vector - three hidden layers - single output" neural network. 
  For the hidden layers we consider the ReLU activation function and for the output the identity function.
  The cost function used in the calculations is the sum of squared errors and the network is trained with a "minibatch SGD" optimizer
  
- The "dataset_classification_1" and "dataset_classification_2" files contain applications of the network in circular and moon-shaped datasets respectively. 
  In both cases we tune the network with Grid Search in order to get the best performing model. 
  We draw the resulting classifiers which separate the training datasets with 99% and 98% accuracy respectively. 
  In addition, we test them over unseen data and achieve 94% and 100% accuracies respectively.
