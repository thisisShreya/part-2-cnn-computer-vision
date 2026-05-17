# part-2-cnn-computer-vision

# CNN Computer Vision Prototype

## Problem Type

This project represents an Image Classification problem because the model predicts the class label of an input image.

## Dataset Exploration

The dataset contains multiple image classes used for classification.

Dataset analysis included:
- Number of classes
- Number of images per class
- Sample image visualization
- Image dimensions
- Class imbalance analysis

## Image Preprocessing

The following preprocessing steps were performed:
- Image resizing to 128x128
- Pixel normalization
- Data augmentation
- Train-validation split

## CNN Architecture

The CNN model includes:
- Convolution layers
- ReLU activation
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

## Model Evaluation

The model was evaluated using:
- Training accuracy
- Validation accuracy
- Loss curves
- Confusion matrix
- Sample predictions

## CNN Concept Explanation

### What is Convolution?

Convolution helps detect patterns such as edges, textures, and shapes from images using filters.

### Why is Pooling Used?

Pooling reduces image dimensions and helps reduce computation while keeping important features.

### Why is ReLU Used?

ReLU introduces non-linearity and helps CNNs learn complex image patterns efficiently.

### Why are CNNs Better for Images?

CNNs automatically learn image features and preserve spatial relationships, unlike regular feed-forward neural networks.

## Business Use Case

This type of computer vision system can be used in healthcare for disease detection from medical images.

## Libraries Used

- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset Source

Dataset provided in assignment Google Drive link.(https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs)
