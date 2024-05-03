# ResNet Implementation in PyTorch
Implementation of the ResNet model in PyTorch. Based on the architecture from the paper: https://arxiv.org/abs/1512.03385.  

Inspired by the torchvision implementation: https://github.com/pytorch/vision/tree/main.

Trained on CIFAR-10 dataset: https://www.cs.toronto.edu/~kriz/cifar.html.

### Settings
epochs: 50  
learning rate: 0.1, divided by 10 when error plateaus  
optimizer: SGD, weight decay 1e-4, momentum 0.9  
batch size: 128  

### Results
|   |         | ResNet-34 |  ResNet-50 |
|---|------------------------|----------------|--------------------------|
|   | # of Trainable Params  | 21.3M | 23.5M |
|   | Test Accuracy | xx.x% | xx.x% |
