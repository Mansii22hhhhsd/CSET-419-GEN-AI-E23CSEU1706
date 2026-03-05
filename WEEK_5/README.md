# Baseline CNN for Image-to-Image Translation

This project implements a **baseline Encoder–Decoder CNN** for image-to-image translation using the **CIFAR-10 dataset**.

## Objective
Train a CNN model to reconstruct **original images from their edge-detected versions** using reconstruction loss.

## Steps
- Load CIFAR-10 dataset
- Generate edge images using Canny edge detection
- Normalize images to `[-1,1]`
- Train an Encoder–Decoder CNN
- Use **MSE / L1 loss**
- Visualize generated images

## Expected Output
The model reconstructs the original images from edges.  
Since this is a simple encoder–decoder model (without GAN), the output images may appear **blurry**.

## Tools
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

---
