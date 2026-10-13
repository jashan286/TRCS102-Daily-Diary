# Session 25: Introduction to Neural Networks

## Topics Covered
- Introduction to Neural Networks
- Structure of an Artificial Neural Network (ANN)
- Neurons, Weights, and Biases
- Forward Propagation
- Input, Hidden, and Output Layers
- Applications of Neural Networks

## Key Learnings

### 1. Introduction to Neural Networks
A Neural Network is a machine learning model inspired by the structure of the human brain. It learns patterns from data and uses them to make predictions or classifications.

### 2. Structure of a Neural Network
An Artificial Neural Network (ANN) generally consists of three types of layers:

- **Input Layer:** Receives input features from the dataset.
- **Hidden Layer:** Processes information and learns patterns from the data.
- **Output Layer:** Produces the final prediction or result.

A neural network may contain multiple hidden layers.

### 3. Basic Components
- **Neurons:** Basic processing units that receive and process information.
- **Weights:** Determine the importance of different inputs.
- **Bias:** Helps adjust a neuron's output.
- **Activation Function:** Introduces non-linearity so the network can learn complex patterns.

### 4. Forward Propagation
Forward propagation is the process of passing input data through the network to generate an output.

Each neuron calculates a weighted sum of its inputs, adds a bias, and applies an activation function.

The basic formula is:

**z = Σ(wx) + b**

Where:
- `x` = Input
- `w` = Weight
- `b` = Bias
- `z` = Weighted sum before activation

### 5. How Neural Networks Learn
Neural networks learn by comparing their predictions with the actual results using a loss function. During training, weights and biases are adjusted to reduce prediction errors.

Backpropagation and optimization algorithms are commonly used for this learning process.

### 6. Applications of Neural Networks
- Image and face recognition
- Speech recognition
- Medical diagnosis support
- Natural Language Processing (NLP)
- Fraud detection
- Recommendation systems

## Common Python Tools
- `TensorFlow` – Framework for building and training neural networks.
- `Keras` – High-level API for creating neural network models.
- `PyTorch` – Framework for deep learning.
- `Sequential()` – Creates a sequential neural network model in Keras.
- `Dense()` – Adds a fully connected layer.
- `compile()` – Configures the model for training.
- `fit()` – Trains the model.

## Key Takeaways
- Neural networks are inspired by the human brain.
- An ANN contains input, hidden, and output layers.
- Weights and biases influence neuron outputs.
- Activation functions help networks learn complex patterns.
- Neural networks learn by adjusting their parameters to reduce errors.
- They are widely used in deep learning applications.

## Summary
In this session, I learned the fundamentals of Artificial Neural Networks, including their structure and basic components. I studied neurons, weights, biases, and forward propagation. I also explored how neural networks learn from data and their applications in image recognition, speech processing, and other fields.
