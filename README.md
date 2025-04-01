# Car-Detection
A clean implementation of YOLO (You Only Look Once) for object detection with:
- **Non-Max Suppression (NMS)**
- **Intersection over Union (IoU)**
- **Bounding box visualization**
![YOLO Detection Example](demo.jpg)


## Features ✨
- ✅ Pre-trained YOLO model (COCO dataset)
- ✅ Efficient NMS implementation
- ✅ IoU calculation for box overlap
- ✅ Clean, modular code structure

YOLO v2.0 model is not limited to just car detection—it can detect 80 different object classes from the COCO dataset (Common Objects in Context).

## What Can This Model also Detect?
The model uses coco_classes.txt, which includes:
- 🚗 Vehicles: Car, Bus, Truck, Motorcycle, Bicycle
- 🚦Traffic Objects: Traffic Light, Stop Sign
- 🐱 Animals: Cat, Dog, Bird, Horse
- 👫 People: Person
- 🪑 Common Objects: Chair, Sofa, Bottle, Laptop
- ## Usage 🖥️
- Place test images in images/ folder
- Run 
- Results saved in out/ folder
## Dependencies 📦
- TensorFlow 2.x
- OpenCV
- NumPy
- Matplotlib
- Pillow
- yad2k

## Credits 🙏
Based on:
- Original YOLO paper: Redmon et al. (2016)
- YAD2K implementation
