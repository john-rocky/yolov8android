# YOLOv8Android sample

<img src=https://github.com/john-rocky/PersonSegmentationSampler/assets/23278992/ed0abc0f-c5f7-48e2-a355-ffb1dc4b76f1 width=200>

# How to use

1,clone this repo

2,open with android studio

3,run

# Thanks

This repository based on 

https://github.com/surendramaran/YOLOv8-TfLite-Object-Detector

# Conversion script pytorch to tflite

```
pip install ultralytics
pip install tensorflow==2.13.0
```

```
from ultralytics import YOLO
model = YOLO('yolov8s.pt')
model.export(format="tflite")
```


