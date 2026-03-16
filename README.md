# 🌿 Plant Disease Recognition System

A Deep Learning based web application that detects plant diseases from leaf images using **TensorFlow and Streamlit**.

This project uses a Convolutional Neural Network (CNN) model trained on a large dataset of plant leaf images to classify different plant diseases and healthy leaves.

---

## 🚀 Features

- Upload plant leaf images for disease detection
- Automatic classification using a trained CNN model
- Simple and interactive Streamlit web interface
- Supports multiple crops and disease categories
- Fast prediction results

---

## 🧠 Model Overview

The model is built using **TensorFlow/Keras** and trained on a dataset containing thousands of labeled plant leaf images.

Dataset Details:

- Total Images: ~87,000
- Training Images: 70,295
- Validation Images: 17,572
- Test Images: 33
- Classes: 38 plant disease categories

The model achieved approximately **97% training accuracy** and **94% validation accuracy**.

---

## 🖥 Application Interface

The application is built using **Streamlit** and contains three main sections:

1. **Home** – Overview of the project  
2. **About** – Information about the dataset and project  
3. **Disease Recognition** – Upload an image to detect plant disease  

Users can upload a plant leaf image and the model predicts the disease class.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Plant-Disease-Recognition-System.git
