# 🧠 Brain Tumor Classification using Deep Learning (CNN)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Keras](https://img.shields.io/badge/Keras-CNN-red)

---

## 📌 Project Overview

This project is a Deep Learning-based Brain Tumor Classification system that detects whether an MRI brain scan image contains a **Benign** or **Malignant** tumor.

The model is built using **Convolutional Neural Networks (CNN)** with **TensorFlow and Keras**.  
It uses data augmentation techniques to improve generalization and performance.

This project demonstrates practical implementation of computer vision and medical image classification using deep learning.

---

## 🎯 Objective

The objective of this project is to assist in early detection of brain tumors using image classification techniques.  
This system can support medical professionals by providing an automated prediction model based on MRI scan images.

---

## 🚀 Key Features

- CNN-based image classification
- Binary classification (Benign vs Malignant)
- Data Augmentation using ImageDataGenerator
- Model training and validation
- Custom image prediction
- Deep Learning workflow implementation

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- ImageDataGenerator
- Deep Learning (CNN Architecture)

---

## 🧠 Model Architecture

The Convolutional Neural Network consists of:

- Conv2D Layers (Feature Extraction)
- MaxPooling Layers (Dimensionality Reduction)
- Flatten Layer
- Fully Connected Dense Layers
- ReLU Activation
- Sigmoid Activation (Binary Output)
- Optimizer: Adam
- Loss Function: Binary Crossentropy

---

## 📂 Project Structure

brain/
│── BTD.py
│── BTD.csv
│── README.md
│── train/
│ ├── benign/
│ └── malignant/
│── test/
│ ├── benign/
│ └── malignant/
│── TestImages/

----


---

## ⚙️ Installation & Setup

### 1️⃣ Install Python (3.x)

Download from:
https://www.python.org/downloads/

---

### 2️⃣ Install Required Libraries

```bash
pip install tensorflow keras numpy

3️⃣ Dataset Directory Structure

Ensure dataset is arranged as:

Brain_tumor/
│── train/
│   ├── benign/
│   └── malignant/
│
│── test/
│   ├── benign/
│   └── malignant/

4️⃣ Run the Project

python BTD.py


The model will train for 100 epochs and perform prediction on test images.

📊 Output Example

The system predicts:

  -> Benign

  -> Malignant

Example:

Detected tumor type is Benign

📈 Future Enhancements

1. Implement Transfer Learning (VGG16 / ResNet)

2. Improve model accuracy

3. Save and load trained model (.h5 file)

4. Build a Flask Web Application for UI

5. Deploy the model on cloud platform

👨‍💻 Author

 -> Penchala Narasimha Meruva
 -> MCA Graduate (2024)
 -> Python & Deep Learning Enthusiast
 -> Aspiring Software Developer

 
---

## ✅ Now Final Step

Save the file → Then run:

```bash
git add README.md
git commit -m "Added professional project documentation"
git push


