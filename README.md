# Handwritten Digit Recognition using CNN

This project demonstrates a **Convolutional Neural Network (CNN)** for recognizing handwritten digits from the **MNIST dataset**. The CNN model is implemented using TensorFlow/Keras and achieves high accuracy on test data.

---

## Features
- **Dataset:** Preprocessed MNIST images (28x28 grayscale images of digits 0-9).
- **Model:** 
  - Two convolutional layers with ReLU activation.
  - Max pooling and dropout layers for regularization.
  - Fully connected dense layers.
- **Performance Metrics:**
  - **Loss:** Categorical Crossentropy.
  - **Optimizer:** Adam.
  - Achieved **test accuracy: ~99%**.
- **Prediction Demo:** Predicts digit labels for user-specified input images.

---

## Dataset
The project uses the **MNIST dataset**:
- Training Set: 60,000 images
- Test Set: 10,000 images

Images are normalized to [0, 1] and labels are one-hot encoded for multi-class classification.

---

## Getting Started
### Prerequisites
Install the required dependencies using the following command:
```bash
pip install -r requirements.txt
