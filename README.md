# 🧬 Breast Cancer Classification Using Deep Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-FF6F00?style=for-the-badge&logo=keras&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)

## 📌 Overview
This repository contains a diagnostic support tool designed to automatically classify medical breast cancer images using advanced Convolutional Neural Network (CNN) architectures. The goal of this research project is to provide a scalable, modular solution for early and accurate cancer detection, targeting a classification accuracy of over 93%.

## 📊 Datasets
This project leverages two distinct medical imaging datasets:
1. **Breast Histopathology Images:** 277,524 RGB image patches (50x50 pixels) extracted from 162 whole slide images.
2. **BUSI Dataset:** Ultrasound images categorized into benign, malignant, and normal classes.

## 🧠 Model Architectures
To ensure high reliability in medical diagnostics, multiple architectures were integrated and evaluated to extract complex features and textures from the scans:
* **CNN + Random Forest**
* **CNN + XG-Boost**
* **CNN + Transformer Model**
* **CNN + Inception V3 (Transfer Learning)**

## 📈 Evaluation Metrics
The models are rigorously evaluated using:
* **Accuracy, Precision, and Recall**
* **AUC-ROC Curve:** To effectively distinguish between cancerous and non-cancerous predictions, minimizing critical false negatives.
* **Confusion Matrix:** To analyze model strengths and areas needing improvement in real-world healthcare applications.

## 👨‍💻 Author
* **Utkarsh Kishor** (CS-2341383)
