# CNN Basics

A collection of PyTorch notebooks exploring Convolutional Neural Networks (CNNs) and Residual Networks (ResNets) for image classification on the CIFAR-10 dataset. The project demonstrates the progression from a baseline CNN to progressively improved ResNet architectures and training strategies.

## Features

- CNN implementation from scratch using PyTorch
- Manual implementation of ResNet residual blocks
- CIFAR-10 data preprocessing and training pipeline
- SGD and AdamW optimizers
- Cosine learning rate scheduling
- GPU (CUDA) support when available

## Project Structure

```text
.
├── cnn.ipynb                          # Baseline CNN model
├── resNet-manual.ipynb                # Manual ResNet implementation
├── resNet-improved copy.ipynb         # Improved ResNet architecture
└── resNet-optimization-Lrschedule.ipynb # ResNet with AdamW and cosine LR scheduler
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/shehryar11w/CNN-basics.git
cd CNN-basics
```

Install the required dependencies:

```bash
pip install torch torchvision matplotlib timm
```

Open any notebook in Jupyter Notebook or VS Code and run the cells to train and evaluate the models.

## Purpose

This project was created to explore:

- Convolutional Neural Networks (CNNs)
- Residual learning with ResNet
- Image classification on CIFAR-10
- Modern optimization techniques and learning rate scheduling
- Deep learning workflows using PyTorch

## License

This project is intended for educational purposes.
