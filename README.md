# brain-tumor-detection
to detect the  tumor in the brain
# Brain Tumor Classification Using Convolutional Neural Networks

This project is a brain tumor classification system that utilizes a Convolutional Neural Network (CNN) to classify medical images of brain tumors. The model classifies the images into four categories: glioma, meningioma, notumor, and pituitary tumors.

The system is designed to take images as input and return the predicted tumor category using a deep learning model trained on brain tumor dataset images.

## Features

- **Brain Tumor Classification**: Classifies brain tumor images into one of the four categories: glioma, meningioma, notumor, or pituitary.
- **Deep Learning Model**: Uses a CNN model built with Keras and TensorFlow.
- **Gradio Interface**: Provides a simple user interface to upload images and receive predictions.
- **Image Preprocessing**: Preprocesses images by resizing, normalization, and encoding labels for training.

## Requirements

Before running the project, make sure you have the following Python libraries installed:

- `tensorflow`
- `numpy`
- `opencv-python`
- `gradio`
- `scikit-learn`

You can install the required libraries by running:

```bash
pip install tensorflow numpy opencv-python gradio scikit-learn
