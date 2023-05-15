# Face Mask Recognition

## Introduction
The emergence of the COVID-19 pandemic in 2019 has had a profound impact on society, leading to significant changes in people's lives. While scientists have developed vaccines in many countries, the use of face masks remains crucial for public interactions to prevent the spread of the virus. However, manually assessing whether individuals are wearing face masks in public settings is a laborious process. Therefore, the development of an automated system to detect face masks has become necessary. In this context, we present a highly accurate and efficient face mask detector algorithm that can determine whether individuals are wearing masks in public places.

## Dataset
The datasets we will be using for this project include a train dataset and a test dataset. The train dataset consists of around 12,500 images, totaling approximately 328.92MB in size. Among these images, 6,000 depict individuals wearing face masks, while the remaining images do not show people wearing masks. These datasets are sourced from Kaggle and are specifically curated for face recognition purposes. To ensure faster training and testing times and to demonstrate the model's live functionality, we have also incorporated a smaller dataset. This smaller dataset contains approximately 1,376 photos, with 690 images showing individuals wearing masks and 686 images showing individuals without masks.

## Tech Stack Used
The project involves utilizing Python programming language along with deep learning techniques, specifically leveraging the Keras library. Additionally, OpenCV will be used for computer vision tasks, and MongoDB will serve as the database for storing relevant data.

## Decoding the Code
During the training phase, the model was trained for 20 iterations to improve accuracy without overfitting. The training set achieved an accuracy of 97.86%, while the test set achieved an accuracy of 99.22%. These results indicate that the model is suitable and not overfitting. To perform real-time face mask recognition, the project utilizes a continuous loop implemented with the OpenCV library. The webcam captures the face, and the model analyzes it to classify it into two categories: mask or no mask. The output is determined based on the higher probability assigned by the model.

## Summary
The primary objective of this project is to accurately determine whether a person is wearing a face mask or not. Python and Keras were utilized to design the project, allowing for the identification of facial features such as eyes, eyebrows, and other relevant characteristics. The Kaggle dataset was used for training and testing, while OpenCV was employed to validate the observations made. By combining all the components of our architecture, we aim to create a highly accurate system for detecting face masks. The resulting system demonstrates promising performance in identifying face masks within images, even in the presence of multiple faces and varying angles.

## Output
### With Mask

<img src="withmaskouput.jpeg">

### Without Mask

<img src="withoutmaskoutput.png">
