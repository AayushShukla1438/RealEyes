# 🔍 RealEyes — Advanced Deepfake Detection Using Deep Learning

RealEyes is a full-stack deepfake-detection system engineered to identify manipulated or AI-generated face images with high accuracy.  
Built using **custom CNN-based feature extraction**, **clean preprocessing**, and a **lightweight inference API**, RealEyes serves as a foundation for real-world AI-forensics tools.

> ⭐ If RealEyes helps you, please **Star this repo** — it keeps the project alive.

---

## 📌 Table of Contents
- [Introduction](#-introduction)
- [Key Features](#-key-features)
- [Model Overview](#-model-overview)
- [Training Pipeline](#-training-pipeline)
- [Why Deepfakes Are Detectable](#-why-deepfakes-are-detectable)
- [Tech Stack](#-tech-stack)
- [Author](#-author)
- [Support](#-support)

---

## 🧠 Introduction

Deepfakes are one of the fastest-growing threats in digital media — used for misinformation, identity fraud, political manipulation, and cybercrime.  
RealEyes provides an end-to-end workflow to detect these manipulated images using deep learning.

RealEyes is built to be:

- **Simple** — easy to run locally  
- **Modular** — clean, scalable codebase  
- **Accurate** — trained on real & fake facial datasets  
- **Extensible** — ready for video detection, LSTMs, GRUs, and more  

---

## ⭐ Key Features

### 🧪 ML Features
- Custom CNN architecture (.keras model)
- High-accuracy Real/Fake classification
- Confidence score output
- Automatic image preprocessing pipeline
- Generalizes to unseen fake/real images

### 🖥️ Product Features
- Image upload interface  
- Minimal frontend for fast testing  
- Backend API for prediction  
- Clean logs & error handling  
- Easy extension to REST API or cloud model host  

---

## 📊 Model Overview

| Component      | Details                          |
|----------------|----------------------------------|
| Input Size     | 224×224                          |
| Model Type     | Custom CNN (TensorFlow/Keras)    |
| Output         | Binary (Real / Fake) + Confidence|
| Loss Function  | Binary Cross Entropy             |
| Optimizer      | Adam                             |
| Regularization | Dropout + Augmentation           |

### Training Dataset:
- A balanced set of **real** and **deepfake images**
- Includes:
  - Face-swapped fakes  
  - GAN-generated faces  
  - Blended/manipulated facial regions  

---

## 🔧 Training Pipeline

### 1️⃣ Data Preparation
- Load real/fake image dataset  
- Face-alignment (optional)  
- Resize → Normalize → Augment  

### 2️⃣ Augmentation Includes:
- Random horizontal flips  
- Brightness/Contrast jitter  
- Noise injection  
- Slight random zoom  

### 3️⃣ Model Training
- Early stopping to prevent overfitting  
- Validation monitoring  
- Batch training with efficient caching  

### 4️⃣ Inference Pipeline
```
Uploaded Image
   ↓
Preprocessing (resize, normalize)
   ↓
Model.predict()
   ↓
Real / Fake + Confidence
```

---

## 🕵️ Why Deepfakes Are Detectable

Deepfake models often leave subtle artifacts:

### 🔹 Texture Mismatches  
Skin texture inconsistencies due to GAN limitations.

### 🔹 Facial Boundary Artifacts  
Blending edges between replacement face and original frame.

### 🔹 Lighting Inconsistency  
Unnatural shadow direction or inconsistent highlights.

### 🔹 Irregular Eyes/Teeth Features  
Small distortions missed by generative models.

RealEyes' CNN is trained specifically to detect these micro-patterns.

---

## 🛠️ Tech Stack

### **Machine Learning**
- TensorFlow  
- Keras  

### **Backend**
- Python  
- FastAPI / Flask (depending on version)  

### **Frontend**
- HTML / CSS / JS (minimal)  

### **Utilities**
- NumPy  
- Pillow  
- OpenCV  

---

## 👤 Author

**Aayush Shukla**  


---

## ⭐ Support

If you found RealEyes helpful:

- ⭐ **Star this repository**
- 🔄 Share it with your community
- 💬 Drop suggestions or open issues

Your support keeps the project evolving.

---
