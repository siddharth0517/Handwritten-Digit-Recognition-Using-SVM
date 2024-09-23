# Handwritten Digit Recognition Using SVM
This project implements a **Handwritten Digit Recognition system** using a **Support Vector Machine (SVM)**. The model is trained on the popular **MNIST dataset** and is capable of predicting handwritten digits with high accuracy.

## Table of Contents
+ Introduction
+ Project Overview
+ Dataset
+ Technologies Used
+ Model Performance
+ Contributing

## Introduction
Handwritten digit recognition is a fundamental problem in computer vision. This project uses the MNIST dataset, a well-known dataset of handwritten digits (0-9), and applies an SVM classifier to predict the digit from an image.

## Project Overview
The primary goal of this project is to classify handwritten digits using an SVM model. The pipeline includes:

+ Loading and preprocessing the dataset.
+ Normalizing the image pixel values.
+ Training an SVM classifier.
+ Evaluating the model using accuracy, confusion matrix, and classification report.

## Dataset
The project uses the MNIST dataset, which contains:

+ 60,000 training images of handwritten digits.
+ 10,000 testing images.
+ Each image is a 28x28 grayscale image, flattened into a 784-dimensional feature vector.

## Technologies Used
+ **Python:** Core language for implementation.
+ **scikit-learn:** For building the SVM classifier.
+ **Pandas & NumPy:** For data manipulation and numerical computations.
+ **Matplotlib & Seaborn:** For visualizing results.

## Model Performance
The trained SVM model achieves the following performance:

+ Accuracy: **~96%** on the test set.

## Confusion Matrix
The confusion matrix illustrates how well the model predicts each digit.
![image](https://github.com/user-attachments/assets/8e0bb34c-a826-4381-b6d2-7bd419062b3e)


## Contributing
Contributions are welcome! If you have any suggestions, feel free to open a pull request or an issue.

