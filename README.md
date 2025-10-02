# Logic Gate Neural Network

A simple neural network implementation from scratch using NumPy to classify basic logic gates (AND, OR, NAND, NOR, NOT).

## Features

- 2-layer neural network with configurable hidden neurons
- Sigmoid activation function
- Binary cross-entropy loss
- Backpropagation with gradient descent
- Supports 5 logic gates

## Usage

Run the notebook and input your desired gate:

```python
gate = input()  # Enter: AND, OR, NAND, NOR, or NOT
```

The network will train and output predictions for all input combinations.

## Architecture

- Input Layer: 2 neurons (or 1 for NOT gate)
- Hidden Layer: 2 neurons
- Output Layer: 1 neuron
- Activation: Sigmoid
- Optimizer: Gradient Descent

## Hyperparameters

```python
hiddenneuron = 2
epoch = 100000
learningRate = 0.01
```

## Example Output

```
Epoch 0, Loss: 1.188344
Epoch 10000, Loss: 0.094079
...
Final output for AND gate:
[[0 0 0 1]]
```
