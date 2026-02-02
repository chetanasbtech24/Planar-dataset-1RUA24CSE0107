Assignment 2 – Planar Data Classification using Neural Networks

Overview
This project is Assignment 2, which focuses on implementing a two-class classification model using Logistic Regression and a Neural Network with a single hidden layer. The assignment demonstrates building a neural network from scratch, including forward propagation, backward propagation, loss computation, and parameter updates using gradient descent.

Objectives
Implement a two-class classification neural network
Use tanh activation function in the hidden layer
Use sigmoid activation function in the output layer
Compute cross-entropy loss
Perform forward and backward propagation
Train the model and visualize decision boundaries

Project Structure
Assignment_2 folder contains:
Planar.ipynb – Main Jupyter Notebook with full implementation and results
planar_utils.py – Utility functions for dataset loading and helper methods
testCases_v2.py – Test cases for validating implemented functions
README.md – Project documentation

Dataset
The Planar (Flower) dataset is used.
It is a non-linearly separable dataset.
The dataset is loaded using helper functions provided in planar_utils.py.

Technologies Used
Python
NumPy
Matplotlib
scikit-learn
Jupyter Notebook

Implementation Details

Logistic Regression
Logistic regression is implemented using scikit-learn as a baseline model.
It performs poorly on the planar dataset due to non-linear decision boundaries.

Neural Network Model
The neural network consists of one hidden layer.
The hidden layer uses tanh activation.
The output layer uses sigmoid activation.
Binary cross-entropy loss is used.
Parameters are updated using gradient descent.

Results
Logistic regression achieves low accuracy on the planar dataset.
The neural network achieves higher accuracy.
The cost decreases steadily during training, indicating proper learning.
Decision boundary plots show effective classification.

Notes
Some illustrative images in the notebook may not render properly on GitHub.
These images are for explanation purposes only and do not affect execution.
All code cells execute correctly and produce the expected outputs.

How to Run
Clone the repository.
Open Planar.ipynb in Jupyter Notebook.
Run all cells sequentially.

Author
Chetana S
B.Tech – Data Science
