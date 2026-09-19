# MNIST Digit Classification

## 👨‍🎓 Student Information

**Name:** Darshan.D  
**Course:** B.Tech – Computer Science and Engineering (CSE)  
**Semester:** 5th Semester  
**UEN:** RTU24101CS015  
**College:** Rai Technology University, Bangalore  

---

## 📌 Project Description

MNIST Digit Classification is a Deep Learning project that recognizes handwritten digits from 0 to 9.

The project uses the MNIST dataset, where each handwritten digit is represented as a 28 × 28 grayscale image. A neural network is trained to learn the patterns in these images and classify new handwritten digit images.

---

## 🚀 Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/d2535358-web/Mnist-Digit-Classification/blob/main/MNIST_DIGIT_CLASSIFICATION.ipynb)

Click the button above to open and run the complete project in Google Colab.

---

## 🎯 Objective

The main objective of this project is to develop a simple Deep Learning model that can accurately classify handwritten digits using the MNIST dataset.

---

## 📊 Dataset

The project uses the MNIST Handwritten Digit Dataset.

- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10
- Classes: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
- Image type: Grayscale

---

## 🧠 Model Architecture

The project uses a simple Artificial Neural Network built with TensorFlow and Keras.

### Layers

1. Input Layer – accepts 28 × 28 pixel images
2. Flatten Layer – converts the image into a 784-element vector
3. Dense Layer – 128 neurons with ReLU activation
4. Output Layer – 10 neurons with Softmax activation

### Model Code

```python
model = tf.keras.Sequential([
    tf.keras.Input(shape=(28, 28)),
    tf.keras.layers.Flatten(),
    tf.keras.layers.Dense(128, activation='relu'),
    tf.keras.layers.Dense(10, activation='softmax')
])
