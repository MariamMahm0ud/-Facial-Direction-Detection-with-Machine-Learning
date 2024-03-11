# Facial Direction Detection with Machine Learning
![image](https://github.com/MariamMahm0ud/-Facial-Direction-Detection-with-Machine-Learning/assets/159249412/159ba3e6-de88-4c76-be1e-247e4a2c2dd4)

This project focuses on detecting facial direction, specifically the yaw, pitch, and roll angles, using machine learning techniques. By utilizing facial landmark detection and machine learning models, it predicts the orientation of faces in images and videos.

## Overview

Facial direction detection plays a crucial role in various applications such as facial recognition, augmented reality, driver monitoring systems, and human-computer interaction. This project aims to provide a robust and efficient solution for accurately determining the orientation of human faces in real-world scenarios.

## Features

- Utilizes MediaPipe FaceMesh for facial landmark detection.
- Normalizes facial landmark points to improve model performance.
- Trains machine learning models (e.g., XGBoost, Support Vector Regression) to predict yaw, pitch, and roll angles.
- Visualizes the predicted orientation by drawing a 3D axis on the detected faces.
- Supports both image and video processing for real-time facial direction detection.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Matplotlib (for visualization)
- scikit-learn (for machine learning models)

## Usage

1. Install the required dependencies .
2. Run the provided scripts or integrate the functionality into your own Python projects.
3. Adjust hyperparameters, model architectures, and preprocessing techniques as needed for your specific use case.
4. Ensure that sufficient training data is available and properly labeled for training the machine learning models.
5. Test the system with various images and videos to evaluate its accuracy and performance.


