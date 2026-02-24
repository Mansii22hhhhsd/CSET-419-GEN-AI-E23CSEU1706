# CSET419 – Introduction to Generative AI  
## Lab 3 – Variational Autoencoder (VAE)

### 📌 Objective
In this lab, we implemented a **Variational Autoencoder (VAE)** to understand how generative models learn latent representations and generate new data samples.

The goal was to:
- Learn compressed latent representations
- Generate new images from the learned distribution
- Understand Encoder, Decoder, Latent Space and KL-Divergence

---

### 🧠 Theory Overview
A **Variational Autoencoder (VAE)** is a probabilistic generative model.  
Unlike a standard Autoencoder that learns fixed latent vectors, a VAE learns a **distribution (mean and variance)** in the latent space.

It uses:
- Encoder → Learns μ (mean) and log(σ²)
- Reparameterization Trick → Enables backpropagation
- Decoder → Reconstructs images from latent vectors
- Loss Function → Reconstruction Loss + KL Divergence

---

### 🧪 Tasks Performed

#### 1️⃣ Dataset Preparation
- Loaded MNIST / Fashion-MNIST dataset  
- Normalized image data  
- Split into training and testing sets  

#### 3️⃣ Loss Function
- Reconstruction Loss (Binary Cross Entropy / MSE)  
- KL Divergence Loss  
- Combined both losses  

#### 4️⃣ Model Training
- Trained VAE for multiple epochs  
- Monitored training and validation loss  

#### 5️⃣ Sample Generation
- Sampled random latent vectors from standard normal distribution  
- Generated new images using Decoder  
