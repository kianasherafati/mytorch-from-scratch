# MyTorch from Scratch

An educational neural network framework built with Python and NumPy to explore automatic differentiation and model training.

The implementation includes a tensor dependency graph with backpropagation, dense layers, activation and loss functions, and optimizers including SGD, momentum, RMSProp, and Adam. Some components, including the convolution layer, remain unfinished exercises.

## Explore

- [Tensor and differentiation operations](PRJ1_40131022/mytorch/tensor.py)
- [Dense layer](PRJ1_40131022/mytorch/layer/linear.py) and [optimizers](PRJ1_40131022/mytorch/optimizer)
- [First experiment notebook](PRJ1_40131022/task1.ipynb) and [second experiment notebook](PRJ1_40131022/task2.ipynb)

Open the notebooks from `PRJ1_40131022/` so the local `mytorch` package can be imported. Review their imports for experiment-specific dependencies.

## Acknowledgment

The tensor implementation credits [rs-dl-framework](https://github.com/amirrezarajabi/rs-dl-framework/blob/main/rsdl/tensors.py) as inspiration. This repository is a learning project, with no claim of feature parity with PyTorch.
