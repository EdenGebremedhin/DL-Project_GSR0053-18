# 🚀 Image Denoising using Convolutional Autoencoder

> Deep Learning project for removing noise from MNIST images using a Convolutional Autoencoder (CAE) built with TensorFlow/Keras.

---

## 📌 Overview
This project focuses on building a **Convolutional Autoencoder (CAE)** that learns to remove noise from corrupted images.  
The model is trained on the MNIST dataset where Gaussian noise is added to simulate real-world image degradation.

The goal is to reconstruct clean images while preserving important structural details of handwritten digits.

---

## 🧠 Model Architecture
- **Encoder:** Extracts compressed feature representations using convolution + pooling layers  
- **Decoder:** Reconstructs images using upsampling + convolution layers  
- **Latent Space:** Compact representation of input images  

---

## 📊 Dataset
- MNIST handwritten digit dataset  
- 28×28 grayscale images  
- Gaussian noise applied to inputs  

---

## ⚙️ Tech Stack
- Python 🐍  
- TensorFlow / Keras 🤖  
- NumPy  
- Matplotlib  

---

## 🏗️ Workflow
1. Load MNIST dataset  
2. Normalize images  
3. Add Gaussian noise  
4. Build Convolutional Autoencoder  
5. Train model (noisy → clean mapping)  
6. Evaluate performance  

---

## 📈 Results

The model successfully removes noise while preserving digit structure.

**Evaluation Metrics:**
- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)

✔ Clear reconstruction of digits  
✔ Strong noise reduction  
✔ Slight blurring in fine details  

---

## 🖼️ Sample Output

![Result](results/sample_output.png)

```md
Noisy Image → Clean Image → Reconstructed Image
