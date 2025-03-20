# Malaria_Detector

Overview
This project implements a Convolutional Neural Network (CNN) to classify microscopic blood cell images as malaria-infected or healthy. The dataset undergoes preprocessing, including image resizing and normalization, before being fed into the CNN model for training.

Model Architecture
Convolutional layers for feature extraction
Pooling layers to reduce dimensionality
Fully connected layers for classification
Softmax activation for binary classification
Training
The model is trained using the Adam optimizer with a categorical cross-entropy loss function. Training runs for multiple epochs, and the dataset is augmented to improve generalization.

