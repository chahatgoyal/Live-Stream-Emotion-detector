# Live-Stream-Emotion-detector
This model is based on CNN , transfer learning and is used to detect emotion and to apply facial recognition
Introduction
This project aims to classify the emotion on a person's face into one of seven categories,
using deep convolutional neural networks. This repository is an implementation of this research paper.
The model is trained on the FER-2013 dataset which was published on International Conference on Machine Learning (ICML).
This dataset consists of 35887 grayscale, 48x48 sized face images
with seven emotions - angry, disgusted, fearful, happy, neutral, sad and surprised.

Link for the dataset
https://www.kaggle.com/deadskull7/fer2013

Algorithm

First, the haar cascade method is used to detect faces in each frame of the webcam feed.

The region of image containing the face is resized to 48x48 and is passed as input to the CNN.

The network outputs a list of softmax scores for the seven classes of emotions.

The emotion with maximum score is displayed on the screen.








