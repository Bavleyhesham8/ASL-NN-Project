# 🤟 ASL-NN-Project: Deep Learning for American Sign Language Recognition

Welcome to our  project repository, where we tackle **American Sign Language (ASL) recognition** using powerful deep learning models. Our goal is to develop a robust 
neural network-based system to classify ASL hand signs accurately.


---

##  Team Members

This project was developed by undergraduate students in the **Artificial Intelligence Department**,  
**Faculty of Computers and Artificial Intelligence, Benha University**:

- **Ahmed Salem**
- **Gamal Ali**
- **Kirllos Henin**
- **Mohamed Ramadan**
- **Bavley Hesham**
---

## 📌 Project Overview

This project focuses on building and comparing various deep learning architectures for **image classification** of ASL gestures. We trained and evaluated models using a labeled ASL image dataset and performed extensive analysis to determine the best-performing architecture.

We also developed a **mobile application** that uses the trained MobileNet model to recognize ASL gestures in real-time using the device camera. The app predicts the detected alphabet along with the **confidence percentage**.

---

## 🧠 Models Implemented

We experimented with multiple deep learning models, including:

- ✅ **CNN from scratch**
- ✅ **VGG16**
- ✅ **ResNet**
- ✅ **DenseNet**
- ✅ **MobileNet** *(used in the mobile app)*

Each model was trained, validated, and evaluated using a structured pipeline. Performance metrics and visualization results were used to assess their effectiveness.

---

## 📱 Mobile Application (ASL Detector)

We built a mobile app that:

- Captures ASL gestures using the device’s **camera**
- Uses a **MobileNet** model to predict the corresponding **ASL alphabet**
- Displays the **confidence score** for each prediction in real-time

The app is lightweight and optimized for mobile inference using TensorFlow Lite.

---

## 📊 Evaluation Metrics

We evaluated our models using:

- **Accuracy**
- **Precision / Recall / F1-Score**
- **Confusion Matrix**
- **Loss and Accuracy Curves**

---

## 📈 Visualization

The project includes detailed visualizations:

- 📉 **Training/Validation Loss & Accuracy plots**
- 🧩 **Confusion matrices**
- 📷 **Random ASL predictions with visual output**
- 📊 **Model performance comparison charts**

---

## 🏁 Results Summary

| Model       | Accuracy | Notes                             |
|-------------|----------|-----------------------------------|
| CNN         | 98.43%      | Custom lightweight model          |
| VGG16       | 99.11%      | Transfer learning, high accuracy  |
| ResNet      | 99.9%      | Deep, robust architecture         |
| DenseNet    | 99.88%      | Efficient gradient flow           |
| MobileNet   | 98.8%      | Lightweight, mobile-friendly      |


---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **TensorFlow Lite** (for mobile deployment)
- **OpenCV**
- **Matplotlib / Seaborn**
- **NumPy / Pandas**
- **Android Studio / Java or Kotlin**
- **Google Colab / Jupyter**

---

