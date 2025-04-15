# Deepfake Detection - Model Training Repository 🎭🧠

This repository contains the model training notebooks for a Deepfake Detection system using various ResNet architectures. Each notebook explores a different depth of ResNet to analyze and compare performance in detecting deepfake images.

## 📁 Notebooks

- `ResNet 18.ipynb` – Lightweight model with faster training, ideal for initial experiments.
- `ResNet 34.ipynb` – Balanced model with moderate complexity and accuracy.
- `ResNet 50.ipynb` – Deeper architecture offering improved feature extraction and performance. (Best Model)
- `ResNet 101.ipynb` – High-capacity model for deeper learning and detailed comparisons.

Each notebook includes:
- Data preprocessing & augmentation  
- Model architecture setup using PyTorch  
- Training & validation loop with live metrics  
- Evaluation using accuracy, precision, recall, F1 score, and confusion matrix  

## 📊 Dataset

- Source: Kaggle
- Classes: `real` and `fake`
- Structure: Train / Test folders with balanced samples

## 🚀 Deployment

The trained model is integrated into a full-stack web app that allows users to upload images and get real-time predictions.

👉 **Check out the app here:** [App Link](https://deepfake-detection-app.netlify.app/)

## 🛠️ Tech Stack

- Python 🐍
- PyTorch 🔥
- Jupyter Notebooks 📓
- ResNet Architectures 🧠
- Matplotlib 📊
- Sklearn 🤖

## 📦 Related Repository

The complete frontend and backend of the deployed web app is available here:  
👉 [Frontend + Backend Repo](https://github.com/cyborgsuh/deepfake-detective)

---

Feel free to ⭐ the repo and share your feedback!
