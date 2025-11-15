# RealEyes — Deepfake Detection Using Deep Learning

Detect deepfake images using a custom-trained deep learning model powered by CNN feature extraction and a fast, lightweight inference pipeline.

> ⭐ If this project helps you, consider giving it a star — it motivates further updates!

---

## 🔍 Overview

RealEyes is an end-to-end deepfake detection system designed to classify images as **REAL** or **FAKE**.  
It includes:

- 🎨 Minimal frontend for image upload  
- ⚙️ Backend API for preprocessing + prediction  
- 🧠 Custom `.keras` deep learning model  
- 📁 Clean, scalable architecture  
- 🚀 Future-ready for video deepfake detection  

---

## 🧠 Core Features

- 🖼️ Detect deepfakes in single images  
- 🧪 Custom-trained Keras CNN model  
- ⚡ Fast preprocessing + inference pipeline  
- 📸 Upload → Preprocess → Predict → Result  
- 🔧 Extendable project structure  
- 💻 Simple to run locally  

---

## 📊 Model Details

| Property       | Value                        |
|----------------|------------------------------|
| Input Size     | **224 × 224**                |
| Architecture   | **CNN-based model**          |
| Framework      | **TensorFlow / Keras**       |
| Output         | **Real / Fake + confidence** |
| Dataset        | Real & Fake face images      |

---

## 🔧 Training Highlights

- Data augmentation  
- Binary cross-entropy loss  
- Adam optimizer  
- Early stopping  
- Clean dataset pipeline  

---

## 🔬 Why It Works

Deepfake images often include subtle artifacts such as:

- irregular facial edges  
- unnatural lighting  
- texture inconsistencies  
- poorly blended regions  

The CNN learns these micro-patterns and generalizes them to unseen images.

---

## 🚀 Future Improvements

- [ ] Full **video** deepfake detection  
- [ ] LSTM + CNN hybrid for temporal analysis  
- [ ] Real-time camera detection  
- [ ] Faster preprocessing pipeline  
- [ ] Public REST API  
- [ ] Cloud deployment (Render / AWS / Azure)  
- [ ] GPU acceleration  

---

## 🧑‍💻 Author

**Aayush Shukla**  
UI/UX • Frontend • ML  
Open for freelance projects & collaborations.

---

## ⭐ Support

If you find RealEyes helpful:  
👉 **Star the repo**  
👉 Share it with your ML/design friends  
👉 Contribute ideas or improvements  

---
