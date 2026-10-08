# Planar Data Classification with One Hidden Layer

This repository contains the programming assignment from the **Deep Learning Specialization** (Course 1: *Neural Networks and Deep Learning*, Week 3) by Andrew Ng on Coursera.

## Overview
The goal of this project is to build a binary classification neural network with a single hidden layer to classify a non-linearly separable dataset (the "flower" dataset) where standard logistic regression fails.

## Key Features & Steps Implemented:
1. **Dataset Analysis & Visualization**: Loading and inspecting the planar flower dataset.
2. **Neural Network Structure**: Defining input ($n_x$), hidden ($n_h$), and output ($n_y$) layer sizes.
3. **Parameter Initialization**: Initializing weights with small random values and biases with zeros.
4. **Forward Propagation**: Implementing linear transformations, `tanh` activation for the hidden layer, and `sigmoid` for the output.
5. **Cost Function**: Computing cross-entropy loss.
6. **Backward Propagation**: Calculating gradients ($dW^{[1]}, db^{[1]}, dW^{[2]}, db^{[2]}$).
7. **Gradient Descent**: Updating parameters using the learning rate.
8. **Model Integration (`nn_model`)**: Combining all steps into a complete training loop.
9. **Prediction & Evaluation**: Testing the model's decision boundary, achieving ~90% accuracy.

## Technologies Used:
* Python
* NumPy
* Matplotlib
* Scikit-learn
