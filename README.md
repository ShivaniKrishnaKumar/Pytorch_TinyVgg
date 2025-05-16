
# TinyVGG Replication with PyTorch

This repository contains a PyTorch-based implementation of the **TinyVGG** architecture, a simplified version of the VGG network typically used for educational and experimental purposes. It walks through the entire pipeline — from data preparation and visualization to model training and evaluation.

- The model is trained and evaluated on the **FashionMNIST** dataset — a collection of 28x28 grayscale images of clothing items, often used as a more challenging alternative to MNIST.

---


## Model Architecture

The TinyVGG model is defined as:

```
Input -> [Conv2d -> ReLU -> Conv2d -> ReLU -> MaxPool2d] x 2 -> Flatten -> Linear
```

- 2 Convolutional Blocks (each block has two Conv layers followed by a MaxPool)
- ReLU activations after each Conv layer
- Final Linear layer for classification

---


## Reference

- [CNN Explainer (VGG-like networks)](https://poloclub.github.io/cnn-explainer/)
- [PyTorch Docs - nn.Module](https://pytorch.org/docs/stable/nn.html)
- [PyTorch Computer Vision](https://www.learnpytorch.io/03_pytorch_computer_vision/)

---
