# Image-Based Nail Disease Identification using CNN

This project is about detecting different types of nail diseases using deep learning. A Convolutional Neural Network (CNN) model was built using TensorFlow and Keras to classify nail images into six categories:

- Blue Finger  
- Acral Lentiginous Melanoma  
- Pitting  
- Onychogryphosis  
- Clubbing  
- Healthy Nail

## Dataset
The dataset includes separate training and validation folders. Images were preprocessed (resized to 128x128 and normalized) before training.

## Model
A CNN model was trained with:
- 3 Convolutional layers (ReLU activation + MaxPooling)
- Flatten and Dense layers
- Dropout layer for regularization
- Categorical crossentropy loss with Adam optimizer

The model was trained for 10 epochs and achieved ~60% validation accuracy.

## Features
- Data preprocessing (resizing, normalization)
- CNN-based classification
- Training and validation accuracy/loss visualization
- Model evaluation on validation set

## Tools Used
- Python
- TensorFlow / Keras
- Matplotlib
- PIL

## Future Improvements
- Use data augmentation to reduce overfitting
- Create a web app for live disease prediction
