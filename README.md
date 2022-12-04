# COMP5511 Assignment2 Task2
## Introduction of task
Use GoogleNet to train and predict the given data set. For unbalanced data, transform is used for data enhancement. The model with data augmentation and the model without data augmentation use the two indicators of accuracy and G-mean to measure the quality of the model. Finally, analyze the experimental results.
## Usage
```python
import os
import json
import torch
import torch.nn as nn
from torchvision import transforms, datasets
import torch.optim as optim
from tqdm import tqdm
import math
from model import GoogLeNet
```
# Operating environment
1. python 3.9.12
2. pycharm
3. windows
# Experimental Results
![2691670137031_ pic](https://user-images.githubusercontent.com/113587800/205478555-8518397e-c6d9-4510-a939-83d1b2766d02.jpg)
![2701670137031_ pic](https://user-images.githubusercontent.com/113587800/205478557-96809181-0fa8-42a6-9389-c39abef0f9fe.jpg)
