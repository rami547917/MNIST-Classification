Custom NumPy-Based Neural Network for MNIST Classification

This project is a minimal implementation of a feedforward neural network from scratch using only NumPy. It classifies handwritten digits from the MNIST dataset, without relying on high-level deep learning frameworks.

I defined a modular architecture using layers like MLP (fully connected), ReLU, and LogSoftmax, all wrapped in a SequentialNN container. The network is trained using Negative Log Likelihood (NLL) loss and manually computed gradients through backpropagation. The Optimizer class handles weight updates via simple gradient descent.

The training process uses mini-batches and runs for 14,000 epochs. After training, I evaluate test accuracy by forwarding each test sample individually.
