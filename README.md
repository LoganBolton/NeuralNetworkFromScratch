# NeuralNetworkFromScratch

## Overview 

Classic MNIST dataset of hand drawn images. I trained this neural network from scratch just using numpy and pandas. 

Current best attempt gets 92% accuracy (!!!!) just using an extremely simple shallow network. 

## Best Results
    - Learning rate: 0.1
    - Epochs: 1,000
    - One hidden layer containing 10x hidden units
    - Extremely basic but works remarkably well

## Experimental changes
Initial experiments with using a learning rate scheduler has not been succesful. High learning rates seem to be very succesful and dropping them down has reduced performance. Need more experimentation