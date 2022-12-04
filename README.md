# COMP5511 Assignment2 Task1
## Introduction of tasks
ResNet (18, 34, 50) and the network without shortcut (18, 34, 50) are used to process the data set, and analyze the network performance effect obtained with and without shortcut.
## Usage
```python
import torch
import torch.nn as nn
import torch.optim as optim
import torchvision
import torchvision.transforms as transforms
import argparse
from resnet import ResNet18, ResNet34, ResNet50
import os
from torch.optim.lr_scheduler import MultiStepLR
from matplotlib import pyplot as plt
```
# Operating environment
1. python 3.9.12
2. pycharm
3. windows
