## Drowsiness Detection - Ultralytics/YOLOv5 Implementation

A simple implementation of the Ultralytics/YOLOv5 implementation.
The model is trained on 40 images - 20 for each label (Drowsy / Awake) on low light settings.

Dependencies
``` python
# dependencies
import torch
from matplotlib import pyplot as plt
import numpy as np
import cv2
import uuid
import os
import time
```
* one
* two
* three

Model import

``` python
# Load the model
model = torch.hub.load('ultralytics/yolov5', 'yolov5s', force_reload='true')
```

Future implementation - loaded on a RaspberryPI or Arduino, to press the espresso machine as Drowsiness detected.

Feel free to use as you wish.
