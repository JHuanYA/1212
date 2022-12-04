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
# Experimental Results
![2651670136615_ pic](https://user-images.githubusercontent.com/113587800/205478383-85dd2f2a-171b-478b-b2e3-513d0b0e9853.jpg)
![2661670136663_ pic](https://user-images.githubusercontent.com/113587800/205478404-2d22b598-6a17-40fe-b99b-035bbee2b512.jpg)
![2671670136663_ pic](https://user-images.githubusercontent.com/113587800/205478411-a9d8ceb4-983a-4579-b12f-dfd40dce56b6.jpg)
