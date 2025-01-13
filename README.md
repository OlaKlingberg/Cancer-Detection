# Detecting Cancer with a Convolutional Neural Network (CNN)

## Background
This project was developed for Module 3 of the course *Introduction to Deep Learning* (DTSA-5511) at University of Colorado Boulder. The task is based on the Kaggle competition [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection).

## Description
In this project, Convolutional Neural Networks (CNNs) are used to detect cancel cels in histopathological images. 

## Data Source
The data can be accessed from the Kaggle page for the competition [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection/data).

## Key Features:
* **Data Preprocessing**: Processes histopathologic images to prepare them for model training, including normalization and augmentation techniques to enhance model robustness.
* **Model Development**: Constructs and compares three different architectures of a Convolutional Neural Network (CNN) tailored: a simple, an intermediate, and a deeper model.
* **Performance Evaluation**: Assesses the models based on accuracy, loss, and Area Under Receiver Operating Characteristic Curve (AUC).

## Results:
The best-performing model was a deeper model, using L2 regularization, which achieved a validation accuracy of 0.887 and validation AUC of 0.974 (run 11 below)

![Results Table](https://github.com/user-attachments/assets/c39c8ad9-a167-4f3b-99f0-5752366cc280)
