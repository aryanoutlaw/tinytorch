
# TinyTorch

A minimalist neural network library built from scratch. TinyTorch provides the essential building blocks for creating and training neural networks, with a focus on simplicity and clarity.

## Features

- **Automatic Differentiation**: Built-in support for backpropagation.
- **Neural Network Modules**: Includes `Neuron`, `Layer`, and `MLP` classes for building networks.
- **Minimalist Design**: Easy to understand and extend.

## Installation

Clone the repository and import the modules directly:

```bash
git clone https://github.com/yourusername/tinytorch.git
cd tinytorch
```

## Usage

```python
from tinytorch.nn import MLP

# Create a multi-layer perceptron
model = MLP(3, [4, 4, 1])

# Forward pass
output = model([1.0, -2.0, 3.0])

# Backward pass
output.backward()
```

## File Structure

```
tinytorch/
├── engine.py  # Core autograd engine
├── nn.py      # Neural network modules
```
