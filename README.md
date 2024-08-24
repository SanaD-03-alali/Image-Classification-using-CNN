# Image Multi-class Classification using CNN
## Project Description

This project implements a Convolutional Neural Network (CNN) from scratch and leverages a pretrained ResNet-101 model to classify images from the [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset/data).

## Model Architecture

The CNN model consists of 6 convolutional layers with the following feature map configurations:
- 3 → 64
- 64 → 128
- 128 → 256
- 256 → 512
- 512 → 512
- 512 → 512

The model also includes:
- 1 fully connected layer with 1024 units
- 1 output layer

The model incorporates batch normalization and max pooling with these hyperparameters:
- Kernel size: 3
- Stride: 1
- Padding: 1
- Pooling window size: 2
- Learning rate: 0.001
- L2 regularization: 1e-3

## Results

The performance of the models is summarized below:

| Model         | Train Accuracy | Validation Accuracy | Test Accuracy | 
|:--------------|---------------:|--------------------:|--------------:|
| **My Model**  | **97.09%**     | **96.37%**          | **96.07%**    |
| **ResNet-101**| **98.44%**     | **98.69%**          | **98.32%**    |

You can download the model after running the code on the dataset.
