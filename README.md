# MNIST Handwritten Digit Classifier

This is a simple deep learning project that builds a neural network using Keras to classify handwritten digits from the MNIST dataset (0–9).

---

## 📌 Overview

- Loads the MNIST dataset (images of size 28×28)
- Preprocesses the data (normalization and one-hot encoding)
- Builds a neural network with two hidden layers
- Trains the model and evaluates it on the test set
- Predicts digits and visualizes both the image and predicted label

---

## 🧠 Model Architecture

- **Input layer:** 784 neurons (flattened 28×28 image)
- **Hidden layer 1:** 300 neurons with ReLU activation
- **Hidden layer 2:** 40 neurons with ReLU activation
- **Output layer:** 10 neurons with softmax activation (for 10 digit classes)

---

## 🚀 Requirements

Install the following Python libraries before running the code:

```bash
pip install numpy matplotlib tensorflow scikit-learn
