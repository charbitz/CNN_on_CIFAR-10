# CNN Training on CIFAR-10

This Colab Notebook was created as part of the **Digital Image Processing** course during the 8th semester at EECE, DUTh. This project represents the second Lab assignment from the course.

## Project Overview

The objective of this project was to train a Convolutional Neural Network (CNN) on the well-known CIFAR-10 image dataset with the goal of achieving a test accuracy near **80%**. 

### Key Constraints:
- **Data Augmentation**: Not allowed.
- **Target Accuracy**: ~80% on the test data.

The model was trained by adjusting various hyperparameters to meet this goal.

## Parameters

The following parameters were customizable for optimizing the CNN's performance:

### General:
- **Batch Size**
- **Epochs**

### Convolutional Layers (Conv2D):
- **Number of Kernels**
- **Activation Function Type**
- **Dropout**
- **Layer Deletion/Modification** (Fully Connected Layer)

### Optimizer:
- **Learning Rate**
- **Decay**

## Results

The final accuracy achieved on the CIFAR-10 test dataset was **79.06%**.

## Dataset

The [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.
