Image Denoising with Convolutional Autoencoder
Project Description

This project uses a Convolutional Autoencoder (CAE) to remove noise from images. It is trained on the MNIST dataset, where Gaussian noise is added to images and the model learns to reconstruct the original clean images.

Dataset
MNIST handwritten digit dataset
28×28 grayscale images
Gaussian noise added for training
Tools Used
Python
TensorFlow / Keras
NumPy
Matplotlib
Model

The model uses:

Encoder: extracts features from noisy images
Decoder: reconstructs clean images from features
Results

The model successfully removes noise and reconstructs clear digit images. Performance is evaluated using PSNR and SSIM.
