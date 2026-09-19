# MNIST Digit Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/d2535358-web/Mnist-Digit-Classification/blob/main/MNIST_DIGIT_CLASSIFICATION.ipynb)

## Project Description

MNIST Digit Classification using Deep Learning.

This project uses:

- TensorFlow
- Keras
- Artificial Neural Network

The project recognizes handwritten digits from **0 to 9** using the MNIST dataset.

The model processes **28 × 28 grayscale images**, trains on handwritten digits, and predicts the correct digit.

## Objective

- To recognize handwritten digits from 0 to 9.
- To build a Deep Learning model using TensorFlow and Keras.
- To preprocess and normalize image data.
- To train the model using the MNIST dataset.
- To evaluate the performance of the trained model.
- To predict handwritten digits accurately.

## Student Details

- **Name:** Darshan.D
- **Course:** B.Tech Computer Science and Engineering
- **Semester:** 5th Semester
- **UEN:** RTU24101CS015
- **College:** Rai Technology University, Bangalore

## Deep Learning Model

The project uses an **Artificial Neural Network (ANN)** built using TensorFlow and Keras.

### Model Layers

1. Input Layer – accepts 28 × 28 pixel images.
2. Flatten Layer – converts the 28 × 28 image into a 784-element vector.
3. Dense Layer – contains 128 neurons.
4. Output Layer – contains 10 neurons for digits 0 to 9.

## Activation Functions

### ReLU

The **ReLU (Rectified Linear Unit)** activation function is used in the hidden Dense layer.

It helps the neural network learn complex patterns from the handwritten images.

### Softmax

The **Softmax** activation function is used in the output layer.

It provides probabilities for the 10 possible digits and selects the digit with the highest probability.

## Dataset

The project uses the **MNIST Handwritten Digit Dataset**.

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Classes: 0–9
- Image Type: Grayscale

## Data Preprocessing

The following preprocessing steps are performed:

- Loading the MNIST dataset.
- Checking sample images.
- Normalizing pixel values between 0 and 1.
- Preparing the images for the neural network.
- Separating training and testing data.
.........
  ## Project Workflow

MNIST Dataset
       ↓
Load Dataset
       ↓
Explore Images
       ↓
Data Preprocessing
       ↓
Normalize Pixel Values
       ↓
Build Deep Learning Model
       ↓
Apply Activation Functions
       ↓
Train Model
       ↓
Evaluate Model
       ↓
Visualize Results
       ↓
Predict Handwritten Digits
-----
Author
Darshan.D
UEN: RTU24101CS015
B.Tech Computer Science and Engineering
5th Semester
Rai Technology University, Bangalore

