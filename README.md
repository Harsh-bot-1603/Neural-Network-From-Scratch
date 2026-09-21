# Neural Network from Scratch

## Description

This project implements a basic neural network from scratch using NumPy, demonstrating fundamental concepts such as dense layers, activation functions (ReLU, Softmax), loss calculation (Categorical Cross-Entropy), backpropagation, and various optimizers (SGD, SGD with Momentum, Adagrad, RMSProp, Adam). It also includes an example of regularization and dropout.

The notebook walks through the following topics:

1.  **Coding a Neuron:** Basic neuron calculation with multiple inputs and a bias.
2.  **Layer of Neurons:** Extending a single neuron to a layer of neurons, first with explicit calculations and then using loops.
3.  **Using NumPy:** Efficient implementation of neurons and layers using NumPy's `dot` product.
4.  **Batches of Data:** Handling multiple samples (batches) simultaneously for training efficiency.
5.  **Implementing Dense Layers:** Creating a `Layer_Dense` class for reusable dense layer components.
6.  **Creating Non-linear Data:** Generating a spiral dataset using `nnfs` for classification tasks.
7.  **Implementing Activation Functions:** Defining `ReLU` and `SoftMax` activation functions as classes.
8.  **One Forward Pass:** Demonstrating a complete forward pass through a simple neural network architecture.
9.  **Categorical Cross-Entropy Loss:** Implementing the loss function to quantify prediction errors.
10. **Backpropagation:** Detailed explanation and implementation of backpropagation for a single neuron and multiple neurons, and integrating it into the `Layer_Dense` and `ReLU` classes.
11. **Combining Softmax and Categorical Cross-Entropy:** Creating a combined `SoftMax_Categorical_Crossentropy` class with its backward pass.
12. **Coding Optimizers:** Implementing various optimization algorithms:
    *   **SGD (Stochastic Gradient Descent)**
    *   **SGD with Learning Rate Decay**
    *   **SGD with Momentum**
    *   **Adagrad Optimizer**
    *   **RMSProp Optimizer**
    *   **Adam Optimizer**
13. **Adding Regularization:** Implementing L1 and L2 regularization to the `Layer_Dense` class and `Loss` class to prevent overfitting.
14. **Dropout:** Implementing a `Layer_Dropout` class to further combat overfitting during training.

## Setup

To run this notebook, you'll need a Python environment with the following libraries:

*   `numpy`
*   `matplotlib`
*   `nnfs`

You can install `nnfs` (which includes numpy as a dependency) using pip:

```bash
pip install --upgrade nnfs
```

## Usage

Simply open the `.ipynb` file in a Jupyter environment (like Google Colab or Jupyter Notebook/Lab) and run the cells sequentially. Each section builds upon the previous ones to gradually construct and train a neural network.
