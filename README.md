## Overview
This project proposes a novel object detection architecture built upon YOLOv10.
While YOLOv10 serves as the baseline, we introduce backbone modifications to improve performance and efficiency for the target task.

## Setup
```
git clone https://github.com/nvdat16/yolov10-modified.git
cd yolov10-modified
pip install -r requirements.txt
```

## Training 
```
yolo detect train data=data.yaml model=model.yaml epochs=50 imgsz=640
```

## Prediction
```
yolo predict predict model=best.pt source='images/'
```

## Trained models
- [Checkpoints](https://drive.google.com/drive/folders/1vBUmMFjJWO1u-sN3oi4d56CTAvOTNBcy?usp=sharing) 

## Note
We will publish the proposed architecture code later.

## Acknowledgement

Our codebase is built based on [yolov10](https://github.com/THU-MIG/yolov10.git). We thank the authors for the nicely organized code!

## References
1. https://github.com/THU-MIG/yolov10.git
2. https://github.com/ChristophReich1996/MaxViT.git
3. https://github.com/fundamentalvision/Deformable-DETR.git