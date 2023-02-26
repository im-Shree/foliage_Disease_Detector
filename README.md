## Foliage_Disease_Detector
  
  This repository contains code for a leaf disease detector using InceptionV3, glob, and ImageDataGenerator. 
  The dataset used for this project contains images of healthy and diseased plant leaves.

## Dataset

  The leaf images data is taken from kaggle. The dataset contains two folders: train and test. 
  The train folder contains subfolders for each class of leaf (healthy or diseased).
  the test folder contains images for testing the model.

## Dependencies

    TensorFlow 2.x
    Keras
    NumPy
    Matplotlib
    glob

## Model Architecture

  We used the InceptionV3 architecture as the base model for our leaf disease detector. 
  We added a GlobalAveragePooling2D layer to flatten the output of the base model. 
  Followed by a Dense layer with 2 units and a softmax activation function to classify the image as healthy or diseased.
  ImageDataGenerator class from Keras to perform data augmentation on the training images.

## Future Work

  Improve the performance of the model by experimenting with different architectures and hyperparameters.
  Use transfer learning to fine-tune a pre-trained model on a larger dataset.
  Deploy the model as a web application or mobile app for real-time leaf disease detection.
