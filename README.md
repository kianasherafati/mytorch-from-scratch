# MyTorch from Scratch

An educational neural network framework built with Python and NumPy to explore automatic differentiation and model training.

The implementation includes a tensor dependency graph with backpropagation, dense layers, activation and loss functions, and optimizers including SGD, momentum, RMSProp, and Adam. Some components, including the convolution layer, remain unfinished exercises in this coursework version.

## Explore

- [Tensor and differentiation operations](mytorch/tensor.py)
- [Dense layer](mytorch/layer/linear.py) and [optimizers](mytorch/optimizer/)
- [First experiment notebook](task1.ipynb) and [second experiment notebook](task2.ipynb)

Open the notebooks from the repository root so the local `mytorch` package can be imported. Review their imports for experiment-specific dependencies.

## Related coursework

[FER2013 Emotion Recognition](https://github.com/kianasherafati/fer2013-emotion-recognition-cnn) contains a later coursework copy of this framework with different convolution and pooling implementations. The two versions remain separate so each experiment retains its original code.

[AI Fundamentals](https://github.com/kianasherafati/ai-fundamentals) covers search, constraints, reinforcement learning, and Bayesian inference. The [original submitted framework archive](archive/mytorch-submission.zip) is retained for reference.

## Acknowledgment

The tensor implementation credits [rs-dl-framework](https://github.com/amirrezarajabi/rs-dl-framework/blob/main/rsdl/tensors.py) as inspiration. This repository is a learning project.
