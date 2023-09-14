# Vehicle-Detection-And-Plate-Recognition

License Plate Recognition is a computer vision project that aims to detect and recognize license plates in images. This project utilizes the YOLOv3 algorithm for vehicle detection and provides multiple methods for license plate localization and character recognition.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#dataset)
- [Pretrained Models](#pretrained-models)
- [Methods](#methods)
- [Performance](#performance)
- [Authors](#authors)

## Introduction
The License Plate Recognition project is designed to detect and recognize license plates in images of vehicles. It utilizes the YOLOv3 algorithm for vehicle detection and provides different methods for license plate localization and character recognition.

## Installation
1. Download the Notebook
2. Upload Project Folder to Drive
3. Upload Notebook to Colab and Run

## Dataset
The project relies on a labeled dataset of vehicle images with license plates for training the YOLOv3 algorithm. Unfortunately, due to licensing restrictions, we are unable to provide the dataset. However, you can use your own dataset or search for publicly available vehicle datasets online.

## Pretrained Models
We provide pretrained models for vehicle detection and character recognition. You can download the models weight file from the following links:
- [YOLOv3 Vehicle Detection Model](https://drive.google.com/file/d/14_HKKduQslakFo85HNmzWxbpeMkzVEFI/view?usp=drive_link)
- [YOLOv3 Car Plate Localization Model](https://drive.google.com/file/d/106XU9ufD6eXnVffwjpV0FguHVirDJ2rH/view?usp=drive_link)
- [YOLOv3 Bike Plate Localization Model](https://drive.google.com/file/d/10A0hFYVtEJFzZZGa7I4TJ_hKPbsSssyO/view?usp=drive_link)

Please place them in the `Project` directory.
If Any Error Download weights from Project folder [Here](https://drive.google.com/drive/folders/1_G0CCQOXOgnFOAg08pFsMQl2Xo5zhC2o?usp=drive_link)

## Methods
### License Plate Localization
This project provides three methods for license plate localization:
1. Custom Trained CNN: A custom convolutional neural network trained specifically for license plate localization.
2. Contour-based Localization: Utilizes contour detection techniques to locate the boundaries of license plates.
3. Haar Cascade Classifier: Uses Haar-like features and a cascade classifier to identify license plate regions.

### Character Recognition
This project offers two methods for character recognition:
1. Transfer Learning with MobileNetV2: Adapts the pre-trained MobileNetV2 model for license plate character recognition.
2. Custom CNN Model: Trains a custom convolutional neural network model for recognizing characters on license plates.

## Performance
The performance of the license plate recognition system may vary depending on the quality of input images, lighting conditions, and other factors. In our evaluation, the system achieves an accuracy of 78% on a benchmark dataset.

## Authors
- Omkar Kanade [@omkarkanade](https://www.github.com/omkarkanade)
- Swarup Kanade [@swarupkanade](https://www.github.com/swarupkanade)
