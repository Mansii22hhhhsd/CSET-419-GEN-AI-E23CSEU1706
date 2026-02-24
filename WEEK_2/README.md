Week 2 – Generative AI Lab
Subject

CSET-419 – Introduction to Generative AI

Experiment 2

Train a Basic GAN Model for Image Generation

Objective

To implement and train a Basic Generative Adversarial Network (GAN) to generate realistic synthetic images using MNIST or Fashion-MNIST dataset and evaluate the generated outputs over training epochs.

Domain Selected

Image Data Generation

Dataset Used

MNIST (Handwritten Digits)
or
Fashion-MNIST (Clothing Images)

Dataset is loaded using TensorFlow/Keras dataset utilities and images are normalized to the range [-1, 1].

Model Architecture
Generator

The Generator takes a random noise vector as input and generates a synthetic image using Dense layers, LeakyReLU activation, Batch Normalization, and tanh activation. The output image size is 28×28×1.

Discriminator

The Discriminator takes an image as input and classifies it as real or fake using Dense layers with LeakyReLU activation and a final sigmoid activation function.

Hyperparameters Used

dataset_choice: 'mnist' or 'fashion'

epochs: 30–100

batch_size: 64 or 128

noise_dim: 50 or 100

learning_rate: 0.0002

save_interval: 5

Optimizer: Adam
Loss Function: Binary Cross-Entropy

Training Process

Train Discriminator on real images (label = 1) and fake images (label = 0).

Train Generator to fool the Discriminator (label = 1 for fake images).

Print epoch-wise logs displaying D_loss, D_acc, and G_loss.

Save generated images at specified intervals.

Output Generated

Training logs printed for each epoch

Folder: generated_samples/ (contains 5×5 image grids saved at intervals)

Folder: final_generated_images/ (contains 100 generated images after training)

Label prediction of generated images using a pre-trained classifier (if implemented)
