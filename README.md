# GAN and CNN Project - School Project

This project explores the use of Generative Adversarial Networks (GANs) and Convolutional Neural Networks (CNNs) for generating and classifying handwritten digits from the MNIST dataset. The homework is divided into two main parts: implementation and exploration of GANs and CNNs, followed by theoretical analysis and latent space exploration.

## Project Overview

### Part 1: GAN and CNN Implementation

1. **GAN (Generative Adversarial Network):**
   - **Objective**: Train a GAN on the MNIST dataset to generate images of handwritten digits.
   - **Components**:
     - **Generator**: Creates fake images based on a latent vector.
     - **Discriminator**: Classifies images as real or fake.
   - **Tasks**:
     - Train GAN on MNIST dataset.
     - Track and analyze loss functions (for both generator and discriminator) and classification accuracy.
     - Improve the model for better image generation.

2. **CNN (Convolutional Neural Network):**
   - **Objective**: Train a CNN for classifying MNIST digits.
   - **Components**: Convolutional layers to extract features, followed by dense layers for classification.
   - **Tasks**:
     - Train the CNN model and report accuracy.
     - Analyze the model’s loss function and classification performance over training.

### Part 2: Latent Space Exploration

1. **GAN Inversion**: Combine the trained generator and classifier to explore the latent space and generate specific images corresponding to desired labels.
   - Generate and select latent vectors to create images with high-quality labels.
   - Analyze how the latent space represents different classes and the effect of varying latent vectors.

2. **Latent Vector Analysis**:
   - **Distribution of Classes**: Check if all classes are equally represented.
   - **Mean Latent Vectors**: Average the latent vectors for each class and generate images.
   - **Interpolation**: Interpolate between latent vectors to explore the transformation between images.
   - **Noise Exploration**: Add noise to latent vectors and observe the changes in generated images.

3. **Message Creation**:
   - **Open Message**: Generate a sequence of digits/letters to form a message using the GAN.
   - **Encrypted Message** (optional): Create a hidden message by saving the latent vectors, which can only be revealed by running the generator.


