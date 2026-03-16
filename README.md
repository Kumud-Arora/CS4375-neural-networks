CS 4375: Machine Learning Assignment 2 - Neural Networks

Author: Kumud Arora

Dataset
-------
Iris Dataset: https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data


Requirements
------------
Python3
pandas
numpy
matplotlib
scikit-learn


How to Run
----------

1. Open the Google Colab file.
2. Run all cells in order.
3. The program will:

   - Load the Iris dataset from the UCI repository
   - Perform preprocessing including:
        • removing null values
        • removing duplicates
        • feature standardization
   - Train neural networks with different hyperparameter combinations
   - Evaluate each model using:
        • training accuracy
        • test accuracy
        • training mean squared error
        • test mean squared error
   - Plot training loss curves for all models
   - Output a table summarizing the performance of each model


Hyperparameters Tested
----------------------

Activation Functions:
- logistic
- tanh
- relu

Learning Rates:
- 0.01
- 0.1

Epochs:
- 100
- 200

Hidden Layer Structures:
- (8,8)
- (8,8,8)


Output
------

1. Training loss curves for each model
2. Table summarizing results for all hyperparameter combinations

Notes
------

I structured the code into functions this time to improve readability, modularity, and reusability, making it easier to maintain and adapt compared to how I'd done it in assignment 1 where the code followed a single linear script structure.
I thought it was a better approach because separating the workflow into functions is closer to a software engineering style of programming, where different parts of the system are modular and easier to test, reuse, and modify.
