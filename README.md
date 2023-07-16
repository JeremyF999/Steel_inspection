# Steel_inspection
# East University Steel Plate Detection Project

This project is aimed at the detection of objects within the East University Steel Plate dataset using an enhanced version of the YOLOv5 model. We've made several improvements that significantly increase the accuracy of detection.

## 1. Dataset

We utilized the East University Steel Plate dataset which initially contained only 1800 images. In order to improve the model's ability to generalize and boost performance, we expanded this dataset to 18000 images using data augmentation techniques.

## 2. Network Improvements

Our model is based on YOLOv5, and we've made the following enhancements:

1. We introduced a BIFPN (Bidirectional Feature Pyramid Network) to strengthen the model's feature extraction capability.
2. We incorporated a GAM (Global Attention Module) to improve the model's feature selection capabilities.
3. We replaced a portion of the network and the C3 module with Ghost Bottlenecks, reducing the model's complexity and improving computation speed.

## 3. Experimental Results

Each enhancement was compared with the original YOLOv5 model to validate the effects of the improvements. Each improvement comes with a comparison chart that clearly demonstrates its effectiveness. Finally, we combined all three improvements and compared them with the original YOLOv5, achieving notable results.

We also conducted comparison experiments with other popular object detection models such as Faster-RCNN, RCNN, and YOLOv7. Below are the visualization charts for these comparison results.
