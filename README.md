# 🥔 Potato Leaf Disease Prediction using CNN

A Deep Learning based web application that detects **potato leaf diseases**
from images using a **Convolutional Neural Network (CNN)** and **Flask**.

---

## 📌 Project Overview

Potato crops are highly affected by diseases such as:

- Early Blight  
- Late Blight  
- Healthy Leaves  

Manual detection is slow and requires expert knowledge.  
This project uses **Computer Vision + Deep Learning** to automatically
classify potato leaf images and assist farmers in **early disease detection**.

---

## 🚀 Features

- Image classification using **CNN**
- Detects **3 classes**:
  - Potato___Early_blight
  - Potato___Late_blight
  - Potato___healthy
- **Flask web app** for easy image upload & prediction
- Data preprocessing & augmentation using **ImageDataGenerator**
- Training visualization:
  - Accuracy & Loss graphs
  - Confusion Matrix
  - Classification Report

---

## 🧠 Tech Stack

- **Python 3.10**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy, Pandas**
- **Matplotlib, Seaborn**
- **Flask**
- **Scikit-learn**

---

## 📂 Project Structure

Potato_Leaf_Disease_Prediction/
│
|
├── model/ # Saved CNN model (.keras)
├── static/ # CSS / uploaded images
├── templates/ # HTML files for Flask
├── app.py # Flask application
├── train_model.ipynb # Model training notebook
├── requirements.txt # Python dependencies
└── README.md # Project documentation

