# Object Detection Using YOLO

## Authors
- Habib Kadiri
- Cyprain Atsyor

## Project Description
This project demonstrates real-time object detection using **YOLO (You Only Look Once)**. The model is 
implemented in Python using PyTorch/TensorFlow and is capable of detecting multiple objects in images and 
video streams with high speed and accuracy. This project is designed for use cases such as **autonomous vehicles,
surveillance, and AI-powered image analysis.**

## Screenshot
![Project Screenshot](https://github.com/habbkad/ai_assignments/blob/main/test1.png)
![Project Screenshot](https://github.com/habbkad/ai_assignments/blob/main/test2.png)
![Project Screenshot](https://github.com/habbkad/ai_assignments/blob/main/test3.png)

## Features
- Real-time object detection with **YOLOv5**
- Pre-trained model support for easy deployment
- Custom dataset training capabilities
- Performance evaluation using **mAP, IoU, and FPS**
- Deployment on **local machines and edge devices**

## Installation & Usage
### Prerequisites
- Python 3.8+
- PyTorch or TensorFlow
- OpenCV
- ultranalytics

### Setup Instructions
```bash
# Clone the repository
git clone https://github.com/habbkad/ai_assignments/tree/main
cd ai_assignment

```


## Repository Structure
```
├── runs/detect/train/weights/          # YOLO model weights
├── datasets/coco8/            # Sample datasets
├── results/         # runs/detect/train
├── detect.py        # Detection script
├── object_detection.ipynb         # Training script
├── README.md        # Project overview
```

## License
MIT License



