# Xavier Initialization in Artificial Neural Networks

## Overview
This project demonstrates **Xavier Initialization (Glorot Initialization)** in Artificial Neural Networks (ANNs). Xavier initialization is designed to maintain a stable variance of activations and gradients across layers, helping to prevent **vanishing and exploding gradient problems** during training.

## Objective
- To understand the need for advanced weight initialization techniques
- To implement Xavier initialization in an ANN
- To analyze its effect on convergence and training stability

## Key Concepts Covered
- Limitations of random and zero initialization
- Xavier (Glorot) initialization theory
- Variance preservation across layers
- Gradient stability during backpropagation
- Improved convergence behavior

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

## Model Architecture
- Input Layer
- Hidden Layers with **tanh / sigmoid activation**
- Output Layer
- Weights initialized using **Xavier initialization**

## Observations
- Faster convergence compared to naive random initialization
- Reduced vanishing gradient effect
- Stable learning across multiple layers
- Better weight distribution during training

## Conclusion
Xavier initialization plays a crucial role in deep neural networks by ensuring balanced signal propagation. It significantly improves learning stability, especially when using **tanh or sigmoid activation functions**.
