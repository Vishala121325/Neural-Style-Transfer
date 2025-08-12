# 🎨 Neural Style Transfer
**Apply the artistic style of one image to the content of another image using deep learning.**

---

## 📌 Overview
This project implements **Neural Style Transfer (NST)** using a pre-trained **VGG19** network.  
Given:
- **Content image** → the base image you want to keep the structure of.
- **Style image** → a famous painting or art whose style you want to apply.

The algorithm blends them to produce a new image that preserves the content but adopts the artistic style.

---

---

## 🚀 Features
- Uses **PyTorch** and a pretrained **VGG19**.
- Supports **custom content** and **style images**.
- Adjustable **style weight** and **content weight**.
- Runs on **GPU** in Google Colab for faster results.
- Saves output images at each stage for progress tracking.

---

## 🛠️ Installation
```bash
# Clone this repository
git clone https://github.com/yourusername/neural-style-transfer.git
cd neural-style-transfer

# Install dependencies
pip install -r requirements.txt
