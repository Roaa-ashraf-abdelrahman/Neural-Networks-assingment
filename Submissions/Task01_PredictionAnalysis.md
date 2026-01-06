# Task 1 - Prediction Analysis

#### How the forward pass transforms inputs through layers?
- by feeding the inputs weights with their bias to perceptrons throughout the hidden layers, it begins as a linear function until it's fed to the activation function which makes introduces non-linearity until we reach the output</br>
#### The role of activation functions (ReLU, Softmax).
- ReLU allows positive values to pass unchanged while setting all negative values to zeros, it helps avoid vanishing gradient problem</br>
- Softmax is useful when we have multiclassification tasks, used in the output layer</br>
#### How the optimizer (Adam) may have shaped weight updates during training.
- Adam optimizer helps with updating learning rate and momentum to update weights to reduce loss as much as possible and it does bias correction

