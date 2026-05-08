# part-2-cnn-computer-vision
# CNN Computer Vision Project

## Problem Type

This dataset represents an Image Classification problem because each image belongs to one specific category such as dent, scratch, stain, or normal.

---

## Dataset Exploration

- Total Classes: 4
  - dent
  - scratch
  - stain
  - normal

- Images were resized to 128x128.
- Data augmentation was applied to improve model performance.
- Dataset was split into training and validation sets.

---

## Image Preprocessing

The following preprocessing techniques were used:

- Image resizing
- Pixel normalization
- Data augmentation
- Training-validation split

---

## CNN Model Architecture

The CNN model includes:

- Convolution Layers
- ReLU Activation Function
- Max Pooling Layers
- Flatten Layer
- Dense Layers
- Softmax Output Layer

---

## CNN Concepts

### What is Convolution?

Convolution helps the model detect important features from images such as edges, textures, and shapes.

### Why is Pooling Used?

Pooling reduces image dimensions and helps reduce computation while keeping important features.

### Why is ReLU Commonly Used?

ReLU helps the network learn non-linear patterns and improves training speed.

### Why are CNNs Better Than Regular Feed-Forward Networks?

CNNs automatically learn image features and preserve spatial relationships, making them more effective for image tasks.

---

## Model Evaluation

The model was evaluated using:

- Accuracy
- Loss Curves
- Confusion Matrix
- Sample Predictions

---

## Business Use Case

This type of computer vision solution can be used in manufacturing industries for automated defect detection in products such as metal surfaces, car parts, or industrial equipment.
