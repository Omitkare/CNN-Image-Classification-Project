# Image Classification Using CNNs - CIFAR-10 Dataset 

This project demonstrates how Convolutional Neural Networks (CNNs) can be used for image classification using the popular CIFAR-10 dataset.

# Objective
To understand the basics of CNNs, implement them using TensorFlow/Keras, and evaluate their performance on the CIFAR-10 image dataset.



# Dataset

- Source: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- Shape:
  - Training set: (50000, 32, 32, 3)
  - Test set: (10000, 32, 32, 3)
- Labels: 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)

---

# Project Structure

# Task 1: Data Exploration and Preparation
- Displayed 5 sample images with labels
- Normalized pixel values to range [0, 1]
- Verified shape and label distribution
- Train-Test split (80%-20%)

# Task 2: Build and Train a CNN Model
- Simple CNN with Conv2D, MaxPooling, Dropout, and Dense layers
- Compiled with optimizer & loss
- Trained for 10–20 epochs
- Visualized training and validation accuracy/loss
- Commented on overfitting/underfitting

# Task 3: Model Evaluation
- Test set accuracy calculated
- Generated classification report and confusion matrix
- Showcased correctly & incorrectly predicted images

# Task 4: Model Improvements
- Tested with other optimizers (SGD, RMSProp)
- Compared model performance in a summary table

---

# Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

