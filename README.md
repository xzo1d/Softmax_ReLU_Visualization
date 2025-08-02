# Softmax_ReLU_visualization

Visualization of Neural Network Training Process and Decision Boundaries
Project Description
This project demonstrates the training process of a simple neural network for classifying a 3D dataset and visualizes the evolution of the network's decision boundaries during training.

Key project stages:

3D Dataset Generation: Creation of a synthetic 3D dataset with three classes. The dataset can be linearly or non-linearly separable, with varying numbers of points and class shapes to demonstrate different training scenarios.
Neural Network Implementation: Building a simple feedforward neural network with one hidden layer using the NumPy library.
Neural Network Training: Training the neural network on the generated dataset using the ADAM optimizer. Network parameters are saved at each epoch during training for subsequent animation.
Visualization:
Displaying the initial 3D dataset.
Creating an animation that shows how the network's decision boundaries change over training epochs.
Visualizing the final decision boundaries after training completion.
Neural Network Architecture
The neural network used is a simple feedforward network with one hidden layer.

Input Layer: Receives 3D input data (3 features).
Hidden Layer: Consists of 25 neurons (the number can be adjusted). Uses the ReLU activation function (max(0, x)).
Output Layer: Has a number of neurons equal to the number of classes in the dataset (3 classes in this project). Uses the Softmax activation function to obtain class probabilities.
Schematic network structure:

Input Layer (3 neurons) -> Hidden Layer (25 neurons, ReLU) -> Output Layer (3 neurons, Softmax)

The neural network is trained to minimize classification error using cross-entropy loss and the ADAM optimizer.
