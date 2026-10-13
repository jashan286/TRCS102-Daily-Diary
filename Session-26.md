# Session 26: Activation Functions and Backpropagation

## Topics Covered
- Introduction to Activation Functions
- Types of Activation Functions
- ReLU, Sigmoid, and Tanh
- Introduction to Backpropagation
- Gradient Descent
- Training Neural Networks

## Key Learnings

### 1. Activation Functions
Activation functions determine the output of a neuron by transforming its weighted sum and bias. They introduce non-linearity, allowing neural networks to learn complex patterns.

### 2. Types of Activation Functions

- **Sigmoid:** Converts values into a range between 0 and 1. It is commonly used in the output layer for binary classification.
- **ReLU (Rectified Linear Unit):** Returns zero for negative inputs and the input itself for positive inputs. It is widely used in hidden layers.
- **Tanh:** Converts values into a range between -1 and 1.
- **Softmax:** Converts output scores into probabilities across multiple classes.

### 3. Introduction to Backpropagation
Backpropagation is an algorithm used to train neural networks. It calculates how much each weight and bias contributes to the prediction error and determines how they should be adjusted.

### 4. Steps in Backpropagation
1. **Forward Propagation:** Pass input data through the network to generate predictions.
2. **Loss Calculation:** Compare predictions with actual values using a loss function.
3. **Backward Propagation:** Calculate gradients of the loss with respect to weights and biases.
4. **Parameter Update:** Adjust weights and biases using an optimization algorithm.
5. **Repeat:** Continue training to reduce the prediction error.

### 5. Gradient Descent
Gradient Descent is an optimization algorithm that updates model parameters in the direction that reduces the loss.

The basic update rule is:

**New Weight = Old Weight − Learning Rate × Gradient**

The learning rate controls the size of each parameter update.

### 6. Importance of Backpropagation
- Helps neural networks learn from errors.
- Updates weights and biases efficiently.
- Reduces the loss during training.
- Supports the training of deep neural networks.

## Common Python Tools
- `TensorFlow` – Framework for neural network training.
- `Keras` – API for building neural network models.
- `ReLU()` – Applies the ReLU activation function.
- `sigmoid` – Applies the sigmoid activation function.
- `softmax` – Converts scores into class probabilities.
- `compile()` – Configures the model with a loss function and optimizer.
- `fit()` – Trains the neural network.

## Key Takeaways
- Activation functions introduce non-linearity into neural networks.
- ReLU, Sigmoid, Tanh, and Softmax serve different purposes.
- Backpropagation calculates gradients to help reduce prediction errors.
- Gradient Descent updates weights and biases.
- The learning rate affects the size of parameter updates.

## Summary
In this session, I learned about activation functions and their role in neural networks. I studied ReLU, Sigmoid, Tanh, and Softmax, along with the steps involved in backpropagation. I also explored Gradient Descent and how neural networks adjust their weights and biases to minimize prediction errors.
