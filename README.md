# Landmark-Detection
This project demonstrates Landmark Detection using TensorFlow and deep learning techniques. The goal is to classify and detect landmarks from images by training a computer vision model. The workflow covers data preprocessing, model development, training, evaluation, and visualization of results.

Google Landmarks Dataset v2 -> https://github.com/cvdfoundation/google-landmark
The above link can be used to access the Landmark Detection Dataset provided by google.

To Visualise the Landmark Searching Features [Image Dataset for Landmarks] -> https://storage.googleapis.com/gld-v2/web/index.html

Dowload the Metadata File(does not contain actual data, links of images to be downloaded) from Google Landmark Dataset (Around 500 MB)
train.csv: CSV with id, url, landmark_id fields. 
          id is a 16-character string, 
          url is a string, 
          landmark_id is an integer.

The training data consists of 500 TAR Files, each file is 1 GB. So 500 GB of Images data.
Use the link to dowload file '000' and '001' and store it in required folder to access dataset in the project

🚀 Features

1.) Loads a landmark image dataset (TensorFlow Datasets or custom).
2.) Performs data preprocessing (resizing, normalization, augmentation).
3.) Implements Convolutional Neural Networks (CNNs) for image classification.
4.) Optionally leverages pre-trained models (e.g., MobileNet, Inception, ResNet) via TensorFlow Hub for transfer learning.
5.) Trains the model with configurable hyperparameters (batch size, epochs, learning rate).
6.) Evaluates performance on validation and test datasets using accuracy and loss metrics.
7.) Visualizes training curves (accuracy/loss vs. epochs).
8.) Generates predictions on test images and displays actual vs. predicted classes.

📈 Results

Achieved high accuracy on validation and test sets
Training/validation accuracy and loss visualized over epochs(Heavy System Requirements : Need to Test 60,000 samples for Accuracy)
Successfully predicted landmark categories on unseen images
