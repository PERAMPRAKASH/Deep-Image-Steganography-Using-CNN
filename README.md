# 🕵️‍♂️ Deep Image Steganography Using CNN

A deep learning project that uses Convolutional Neural Networks (CNNs) to perform **image steganography**—hiding one image inside another while maintaining visual quality and enabling recovery of the hidden image.

---

## 🚀 Features
- Encode a **secret image** into a **cover image** using a deep encoder network.
- Recover the secret image from the generated **container image** using a decoder.
- Uses multiple convolution branches (3x3, 4x4, 5x5) for diverse feature extraction.
- Trained on Tiny ImageNet dataset using TensorFlow/Keras.

---

## 📊 Results
- ✅ MSE < 0.01 between original and reconstructed secret image
- 📈 PSNR > 30dB on test set
- 🔍 Visual similarity between container and cover image is near-perfect
- 🧠 93%+ pixel accuracy in secret image recovery

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Tiny ImageNet Dataset

---

## 🧪 How It Works

### Encoder Network:
1. Applies multi-kernel convolutions to both cover and secret images.
2. Fuses feature maps to generate a container image.

### Decoder Network:
1. Accepts the container image as input.
2. Reconstructs the secret image using inverse CNN operations.

---

## Clone the repo:
```bash
git clone https://github.com/PERAMPRAKASH/Deep-Image-Steganography-Using-CNN

