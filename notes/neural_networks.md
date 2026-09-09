# Neural Networks

## Neuron

A neuron calculates:

z = Wx + b

Each input has a weight.
Each neuron has one bias.

## Linear Layer

nn.Linear(in_features, out_features)

Weights:
in_features × out_features

Biases:
out_features

Total parameters:
(in_features × out_features) + out_features

Example:

nn.Linear(5, 4)

Weights = 5 × 4 = 20
Biases = 4
Total = 24


## ReLU

ReLU(z) = max(0, z)

Negative values → 0
Positive values → unchanged

Purpose:
Introduces non-linearity.


## Sequential

nn.Sequential() connects layers in order.

Example:

Linear → ReLU → Linear → ReLU → Linear