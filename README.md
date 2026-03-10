# 🏥 Kidney Stone Classification using CNN

A Deep Learning project to automate the detection of kidney stones from CT images using Convolutional Neural Networks (CNN).

## 🚀 Project Overview
This repository contains a complete pipeline for image preprocessing, model architecture design, and evaluation of a binary classifier (Stone vs. Non-Stone).

## 📁 Repository Structure
- `notebooks/`: Contains the Google Colab notebook.
- `data/`: Sample images for testing (Original & Augmented).
- `requirements.txt`: List of dependencies.
- `models/`: (Planned) Saved trained model (.h5).

## 🛠️ Tech Stack
- **Framework:** TensorFlow / Keras
- **Image Processing:** OpenCV, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Google Colab

## 🧠 Model Architecture
The model uses a sequential CNN approach:
1. **3 Conv2D Layers:** With BatchNormalization and ReLU activation.
2. **MaxPooling:** For spatial dimension reduction.
3. **Dropout (0.5):** To minimize overfitting.
4. **Dense Layer:** Softmax activation for binary classification.

## ⚠️ Important Note on Data Paths
The code is currently configured to run on **Google Colab** with data mounted from **Google Drive**. 
If you wish to run it locally:
- Change the paths in `Cell 4` to point to your local dataset folders.
- Ensure the folder structure matches: `KINDYS~1/Original Dataset/` and `KINDYS~1/Augmented Dataset/`.

## 📈 Status: Work in Progress
- [x] Data Loading & Augmentation.
- [x] CNN Architecture Design.
- [x] Training Pipeline.
- [ ] **Final Evaluation & Metrics (Results coming soon!)**

## 🔧 How to Setup
1. Clone the repo:
   ```bash
   git clone [https://github.com/SamaWaheed/Deep-Learning-Kidney-Stone-Classification.git](https://github.com/SamaWaheed/Deep-Learning-Kidney-Stone-Classification.git)
