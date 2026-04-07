# Generative AI Lab 8 – Artistic Image Generation using GANs

##  Overview
This project demonstrates how Generative Adversarial Networks (GANs) can generate artistic images by exploring the latent space. The model produces creative outputs that are not direct copies of training data.

## Objective
- Generate artistic images using GANs  
- Explore latent space using random vectors  
- Perform interpolation between latent vectors  
- Visualize generated outputs  

##  Concept
A GAN consists of two neural networks:

- Generator: Generates fake images from random noise  
- Discriminator: Identifies real vs fake images  

Both networks compete with each other, improving the quality of generated images over time.

## Dataset
We used the CIFAR-10 dataset.  
Images are normalized between -1 and 1 for better performance.

##  Model Used
- DCGAN (Deep Convolutional GAN)  
- Uses convolutional layers for stable image generation  

## 🔬 Key Tasks

### 1. Data Preparation
- Load dataset  
- Normalize images  
- Define latent vector size  

### 2. GAN Model
- Build Generator and Discriminator  
- Train using adversarial learning  

### 3. Latent Space Exploration
- Generate images from random noise  
- Interpolate between two latent vectors  
- Observe smooth transitions  

### 4. Artistic Output
- Generate multiple images  
- Visualize diversity and patterns  

## Results
- Generated unique artistic images  
- Smooth transitions observed during interpolation  
- Model learned meaningful visual features  

## Learning Outcomes
- Understanding GAN architecture  
- Importance of latent space  
- Difference between basic and advanced GANs  
- Application of AI in creative fields  

