# Lung-Cancer-Detection-With-CNN
This project implements an efficient convolutional neural network (EFFI-CNN) for detecting lung cancer using CT scan images. The goal is to improve the accuracy and speed of lung cancer detection, contributing to early diagnosis and potentially extending patient life expectancy.
Overview
The EFFI-CNN model is designed with seven layers

Convolution Layer
Max-Pool Layer
Convolution Layer
Max-Pool Layer
Fully Connected Layer
Fully Connected Layer
Soft-Max Layer
The model utilizes lung CT scan images from the LIDC-IDRI and Mendeley datasets to identify cancerous tissues. The architecture leverages the strengths of convolutional layers to extract important features and fully connected layers for classification tasks.

Architecture Details
Input: 224x224x3 lung CT scan images
First Convolution Layer: 3x3 filter, output: 200x200x32
First Max-Pool Layer: output: 100x100x32
Second Convolution Layer: 3x3 filter, output: 50x50x32
Second Max-Pool Layer: output: 25x25x32
Two Fully Connected Layers: output: 25x25x16
Soft-Max Layer: output: 1x224
Results
The EFFI-CNN model is implemented using TensorFlow and has shown promising results in lung cancer detection compared to other methods like ICDSSPLD-CNN and EASPLD-CNN. Key metrics include:

Accuracy: 0.856
Recall Rate: 0.98
Precision: 0.81
Loss on Test Set: 0.856
Future Work
The EFFI-CNN model has demonstrated superior performance in lung cancer detection and shows potential for generalizing to other lung diseases. Future work will focus on expanding the model to cover a wider range of lung conditions.
