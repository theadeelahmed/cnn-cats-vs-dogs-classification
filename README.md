# 🐱🐶 Cats vs Dogs Image Classification using CNN

This project is a **Convolutional Neural Network (CNN)** based image classifier that distinguishes between **cats** and **dogs**.  
Built and trained in **Google Colab**, this project was a key step in my deep learning journey.

## 🚀 Project Overview
The goal of this project was to learn and implement a CNN for **binary classification** and improve model performance by using:
- **Dropout layers** → Reduce overfitting
- **Batch Normalization** → Stabilize and speed up training

The dataset was imported directly from **Kaggle** using the **Kaggle API** and processed using **OpenCV (cv2)** for resizing and preparing images.

## 📚 What I Learned
- Importing datasets using **Kaggle API** (`kaggle.json` authentication)
- Image preprocessing & resizing with **OpenCV (cv2)**
- Designing CNN architectures using:
  - Conv2D layers
  - MaxPooling layers
  - Dropout layers
  - Batch Normalization
  - Dense layers
- How to handle binary classification problems in CNNs
- Training & evaluating models in Google Colab

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- Google Colab
- OpenCV (cv2)
- Matplotlib
- Kaggle API (`kaggle.json`)

## 📊 Model Architecture
1. **Input Layer** – Image input of size `(256, 256, 3)`
2. **Conv2D + MaxPooling** – Extract features from images
3. **Batch Normalization** – Normalize feature maps
4. **Dropout** – Reduce overfitting
5. **Dense Layers** – Fully connected layers
6. **Output Layer** – Sigmoid activation for **binary classification** (Cat or Dog)

## 🏆 Training Results
- **Improved accuracy** after adding Dropout & Batch Normalization
- **Reduced loss** and better generalization on test data

## 📝 Example Predictions
- Input: 🐱 Cat image → Output: **Cat**
- Input: 🐶 Dog image → Output: **Dog**

## 📁 File Structure
- `cats_vs_dogs_cnn.ipynb` → Jupyter Notebook with complete code and model training
- `README.md` → Project details

## 🤝 Acknowledgement
This project was built as part of my learning journey in **Deep Learning** with guidance from my instructor and practical experiments.

## 📬 Connect With Me
- GitHub:https://github.com/theadeelahmed
- LinkedIn:https://www.linkedin.com/in/theadeelahmed

---
⭐ If you find this project helpful, don't forget to star the repo!
