# emotion_detection

Emotion Detection Using CNN & Kaggle Dataset
This repository contains the code for a Convolutional Neural Network (CNN) model trained to detect emotions from facial expressions. The model is based on the FER2013 Kaggle dataset of 48x48 pixel grayscale images of faces. The goal is to classify each face into one of seven distinct emotions.

Project Overview
This project utilizes a basic CNN architecture to categorize facial expressions into the following emotions:

0 = Angry 😡
1 = Disgust 🤢
2 = Fear 😨
3 = Happy 😄
4 = Sad 😢
5 = Surprise 😲
6 = Neutral 😐
The model was trained and tested on the FER2013 dataset, which contains:

Training set: 28,709 images
Test set: 3,589 images
The dataset is preprocessed, and all faces are centered and occupy roughly the same amount of space in each image.

Dataset
The dataset used for this project can be found on Kaggle: 🔗 FER2013 Dataset

How It Works
Model Architecture: A CNN model is implemented to process the grayscale images and predict the corresponding emotion.
Real-time Emotion Detection: The model can be applied to real-time video data, detecting emotions frame by frame.
Video Demonstration: A video showcasing the model’s performance on multiple merged videos is included. You can see how well the model detects emotions in real-world scenarios.
