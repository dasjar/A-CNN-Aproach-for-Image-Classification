# Convolutional Neural Network (CNN) for Image Classification on CIFAR-10

This project involves building and evaluating a Convolutional Neural Network (CNN) to classify images from the **CIFAR-10** dataset. The CIFAR-10 dataset contains 60,000 images across 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The goal of the project is to explore CNN architecture and training strategies, including techniques to prevent overfitting and improve model performance.

## Key Features
- **CNN Architecture**: Multiple convolutional layers, dropout for regularization, batch normalization, and a softmax output layer for multi-class classification.
- **Hyperparameter Tuning**: Grid search for optimizing hyperparameters such as learning rate, batch size, and optimizer.
- **Overfitting Prevention**: Techniques like dropout, early stopping, and batch normalization were employed to improve generalization.
- **Data Augmentation**: 20% of the images were rotated to increase training data diversity.
- **Model Performance**: Achieved a training accuracy of 95.57%, with a validation accuracy of 75.32%, showing some signs of overfitting.

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/cnn-cifar10.git
