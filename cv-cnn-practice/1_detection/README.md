# 1. Object Detection with YOLOv5

This folder contains my hands-on practice for object detection using YOLOv5 on the COCO `val2017` dataset.

## Objectives

- Understand YOLOv5 inference pipeline  
- Compare model sizes and performance (YOLOv5n/s/m/l)  
- Explore precision-recall trade-offs via confidence threshold  
- Investigate effects of input image resolution  
- Evaluate speed vs. accuracy (FPS vs. mAP)  

## Structure

- `yolov5-sia.ipynb`: Main notebook including:
  - Official YOLOv5 usage (inference on val2017)
  - **Experiment 1**: Model size comparison (n/s/m/l)
  - **Experiment 2**: Confidence threshold tuning
  - **Experiment 3**: Input image size effect (320, 416, 640, 832)

## Dataset

- COCO val2017 (person class included in experiments)
- Inference-only usage (no fine-tuning)

## Future Work

- Fine-tuning YOLOv5 on a single class (e.g. `person`)  
- Custom dataset training and evaluation
