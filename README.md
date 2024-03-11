# Facial Direction Detection with Machine Learning
![image](https://github.com/MariamMahm0ud/-Facial-Direction-Detection-with-Machine-Learning/assets/159249412/159ba3e6-de88-4c76-be1e-247e4a2c2dd4)
![image](https://github.com/MariamMahm0ud/-Facial-Direction-Detection-with-Machine-Learning/assets/159249412/c6badc44-c980-4bc9-a9df-25d2b1e2e7a4)

This project focuses on detecting facial direction, specifically the yaw, pitch, and roll angles, using machine learning techniques. By utilizing facial landmark detection and machine learning models, it predicts the orientation of faces in images and videos.
![image](https://github.com/MariamMahm0ud/-Facial-Direction-Detection-with-Machine-Learning/assets/159249412/a3fe7448-da58-4391-be13-d2bd9462ffb7)
![image](https://github.com/MariamMahm0ud/-Facial-Direction-Detection-with-Machine-Learning/assets/159249412/8d1653ec-835a-4ee1-9217-86e94b23e9d5)

## Overview

Facial direction detection plays a crucial role in various applications such as facial recognition, augmented reality, driver monitoring systems, and human-computer interaction. This project aims to provide a robust and efficient solution for accurately determining the orientation of human faces in real-world scenarios.
![image](https://github.com/MariamMahm0ud/-Facial-Direction-Detection-with-Machine-Learning/assets/159249412/3f5e278f-eae8-4e7f-a9df-6b08665266a8)

## Features

- Utilizes MediaPipe FaceMesh for facial landmark detection.
- Normalizes facial landmark points to improve model performance.
- Trains machine learning models ( XGBoost, Support Vector Regression) to predict yaw, pitch, and roll angles.
- Visualizes the predicted orientation by drawing a 3D axis on the detected faces.
- Supports both image and video processing for real-time facial direction detection.
# video processing 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Player</title>
</head>
<body>
    <video width="640" height="360" controls>
        <source src="test data/lucy2.mp4.mp4" type="lucy2/mp4">
        Your browser does not support the video tag.
    </video>
</body>
</html>

[Link to Video](https://drive.google.com/file/d/1BrmK384qTncyv5a_YST-RhSUDKumBTlk/view?usp=sharing)

[![Video Processing](https://drive.google.com/uc?export=download&id=1BrmK384qTncyv5a_YST-RhSUDKumBTlk)](https://drive.google.com/file/d/1BrmK384qTncyv5a_YST-RhSUDKumBTlk/view?usp=sharing)

[![](https://drive.google.com/uc?export=download&id=YOUR_FILE_ID)](https://drive.google.com/file/d/YOUR_FILE_ID/view?usp=sharing)

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


