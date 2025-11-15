RealEyes — Deepfake Detection Using Deep Learning

A complete end-to-end system for detecting deepfake images using a custom deep-learning pipeline.
Built with CNN-based feature extraction and a lightweight inference API, RealEyes aims to make deepfake analysis fast, simple, and accessible.

⭐ If this project helps you, don’t forget to Star the repo — it motivates further updates.

🔍 Overview

RealEyes is a modular deepfake-detection project that uses a custom-trained deep learning model to classify images as REAL or FAKE.
The system includes:

A clean, minimal frontend
A backend API for preprocessing + inference
A trained .keras model
Upload support
Scalable project structure

This project is designed as a foundation for real-world deepfake detection products.

🧠 Core Features

Deepfake detection on single images
Custom-trained Keras model optimized on fake/real face datasets
Fast inference pipeline with preprocessing + prediction
Upload interface (image → prediction)
Extensible folder structure for future video detection
Easy local deployment

📊 Model Details

Input Size: 224×224
Architecture: CNN-based
Training Dataset: Real & Fake face images
Output: Real or Fake + confidence
Framework: TensorFlow / Keras

🔧 Training Highlights

Data augmentation
Loss: Binary cross-entropy
Optimizer: Adam
Early stopping enabled

Why It Works

Deepfake images often show subtle artifacts like:
inconsistent facial edges
unnatural lighting
texture mismatch
blending artifacts
The model learns these patterns from large real/fake datasets and generalizes to unseen inputs.

🧩 Future Improvements

These will make the system production-ready:
 Full video deepfake detection
 LSTM/CNN hybrid for temporal consistency
 Live camera deepfake checks
 Faster preprocessing pipeline
 Public REST API for developers
 Deploy on cloud (Render / AWS / Azure)
 GPU acceleration

🧑‍💻 Author
Aayush Shukla

⭐ Support

If you find this project valuable:

👉 Star this repository
👉 Share it with your ML friends
👉 Contribute ideas or improvements
