# PyTorch Interview Notes

## What is nn.Module?

nn.Module is the base class for creating
custom neural network models in PyTorch.

It allows PyTorch to track parameters,
run forward passes, calculate gradients,
and work with optimizers.

## What is nn.Sequential?

A container that executes layers in order.

Use it for straightforward feed-forward
architectures.

## Difference between backward() and step()

loss.backward()
→ calculates gradients

optimizer.step()
→ updates parameters using gradients