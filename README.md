# Brain Tumor Detection Using CNNs with GradCAM Visualization
# Overview
This repository contains the code for a brain tumor detection project using Convolutional Neural Networks (CNNs). The model was trained on an MRI dataset and achieved a test accuracy of 92%. The project also includes the use of GradCAM for visualizing the areas of the MRI scans that the model focuses on when making its predictions, providing insights into the model's decision-making process.
# Dataset
Dataset Used: [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) from Kaggle.
Classes: The dataset consists of four classes representing different types of brain tumors and healthy brain scans.
# Model Architecture
The CNN model consists of several convolutional layers with ReLU activation and max-pooling, followed by fully connected dense layers. The architecture is designed to capture spatial features from the MRI images, and the final output layer uses softmax activation to classify the images into one of the four classes.
# GradCAM Visualization
GradCAM (Gradient-weighted Class Activation Mapping) is used to generate visual explanations for the CNN's predictions. It highlights the regions in the MRI images that most influence the model's decision, helping users understand which parts of the image the model considers important for classification.
Performance
# Test Accuracy: 92%
