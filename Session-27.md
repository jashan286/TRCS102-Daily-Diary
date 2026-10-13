# Session 27: Building Neural Networks Using TensorFlow and PyTorch

## Topics Covered
- Introduction to TensorFlow and PyTorch
- Building Artificial Neural Networks (ANNs)
- Creating Neural Network Layers
- Model Compilation and Training
- Making Predictions
- Comparing TensorFlow and PyTorch

## Key Learnings

### 1. Introduction to TensorFlow and PyTorch
TensorFlow and PyTorch are popular deep learning frameworks used to build, train, and evaluate neural networks. They provide tools for working with tensors, designing models, and performing automatic differentiation.

### 2. TensorFlow and Keras
TensorFlow is an open-source framework for machine learning. Keras provides a high-level API for building neural networks easily.

Important components:
- `Sequential()` – Creates a model with layers arranged in sequence.
- `Dense()` – Creates a fully connected neural network layer.
- `compile()` – Configures the model with an optimizer and loss function.
- `fit()` – Trains the model using training data.
- `predict()` – Generates predictions for new data.

### 3. PyTorch
PyTorch is a deep learning framework that provides flexible tools for building and training neural networks.

Important components:
- `torch.tensor()` – Creates a tensor.
- `nn.Module` – Base class for defining neural network models.
- `nn.Linear()` – Creates a fully connected layer.
- `torch.optim` – Provides optimization algorithms.
- `loss.backward()` – Calculates gradients through backpropagation.
- `optimizer.step()` – Updates model parameters.

### 4. Basic Steps to Build a Neural Network
1. Import the required libraries.
2. Prepare and preprocess the dataset.
3. Define the neural network architecture.
4. Select a loss function and optimizer.
5. Train the model using training data.
6. Evaluate its performance.
7. Use the trained model to make predictions.

### 5. TensorFlow vs PyTorch

| TensorFlow with Keras | PyTorch |
|---|---|
| Provides a high-level API through Keras. | Provides flexible model-building tools. |
| Uses methods such as `compile()` and `fit()`. | Commonly uses explicit training loops. |
| Suitable for rapid model development and deployment. | Popular for research and flexible experimentation. |

Both frameworks support neural network training, automatic differentiation, and GPU acceleration.

## Common Python Tools
- `tensorflow` – Deep learning framework.
- `keras` – High-level neural network API.
- `torch` – PyTorch library.
- `torch.nn` – Tools for defining neural network layers.
- `torch.optim` – Optimizers for training models.
- `numpy` – Numerical computations and data preparation.

## Key Takeaways
- TensorFlow and PyTorch are widely used deep learning frameworks.
- Keras simplifies neural network development.
- Neural networks consist of layers that process input data.
- Training involves calculating loss and updating model parameters.
- Evaluation helps measure how well a model performs on unseen data.

## Summary
In this session, I learned how TensorFlow, Keras, and PyTorch are used to build neural networks. I studied model architecture, layers, training, evaluation, and prediction. I also compared the major features of TensorFlow and PyTorch and explored their common tools for developing deep learning models.
