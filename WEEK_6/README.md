# Pix2Pix GAN for Image-to-Image Translation

This project implements **Pix2Pix**, a GAN-based model for image-to-image translation.

## Objective
Train a Pix2Pix model to generate **real images from edge images** using a conditional GAN.

## Architecture
- **Generator:** U-Net (encoder–decoder with skip connections)
- **Discriminator:** PatchGAN (classifies image patches as real or fake)

## Training
The model is trained using:
- **Adversarial Loss**
- **L1 Reconstruction Loss**
- **Adam Optimizer (lr = 0.0002)**

## Dataset
Paired dataset (Edges → Real Images), such as **Edges2Shoes**.

## Result
Pix2Pix produces **sharper and more realistic images** compared to the baseline CNN encoder–decoder.

