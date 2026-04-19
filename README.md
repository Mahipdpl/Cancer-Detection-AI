# Early Detection of Cancer using AI

This project implements a Deep Learning approach to classify histopathological images of breast cancer into three categories: **Ductal Carcinoma**, **Lobular Carcinoma**, and **Mucinous Carcinoma**. 

## 🔬 Project Overview
The core of this research is a comparative analysis of different optimization techniques used in Convolutional Neural Networks (CNN). We evaluate how the choice of optimizer affects the accuracy and reliability of cancer detection.

## 🚀 Features
- **Dataset:** BreakHis histopathological image dataset.
- **Architecture:** Convolutional Neural Network (CNN) built with TensorFlow/Keras.
- **Optimizers Compared:** - **ADAM** (Adaptive Moment Estimation)
  - **SGD** (Stochastic Gradient Descent)
  - **Mini-Batch Gradient Descent**
- **GUI:** Interactive desktop application built using Tkinter.

## 📊 Results
In our experimental runs, the **ADAM optimizer** achieved the highest performance metrics, demonstrating its efficiency in handling the complex textures found in medical tissue samples.

## 🛠️ Installation & Usage
1. **Prerequisites:** Python 3.11
2. **Install Libraries:**
   ```bash
   pip install tensorflow opencv-python matplotlib scikit-learn pandas
