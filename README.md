# 🖐️ ASL Sign Language Classifier using CNN

## 📌 Project Overview
This project is a **Sign Language Recognition system** that uses a **Convolutional Neural Network (CNN)** to classify American Sign Language (ASL) hand gestures from images.

The model is trained to recognize different ASL alphabet signs and predict the corresponding letter based on input images.

---

## 🚀 Features
- ASL hand gesture classification using CNN
- Image preprocessing using OpenCV
- Deep learning model built with TensorFlow/Keras
- Trained model saved in `.h5` format
- Simple and easy-to-use prediction pipeline

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset
The dataset contains **87,062 images** of ASL hand gestures.

⚠️ Note:  
The full dataset is not included in this repository due to its large size.

Dataset link (Google Drive or Kaggle):  
👉 https://drive.google.com/file/d/1VlhbrFAKw_WCmXB3EGg8EH26uPu5spZK/view?usp=drive_link

---

## 🧠 Model Architecture
The CNN model consists of:
- Convolutional layers (feature extraction)
- MaxPooling layers (downsampling)
- Flatten layer
- Dense fully connected layers
- Softmax activation for classification

---

## 📊 Results
- The model achieves good accuracy on test data.
- However, results may vary due to:
  - Dataset imbalance
  - Overfitting issues
  - Image quality variations

### 🔮 Future Improvements:
- Data augmentation
- Dropout regularization
- Better CNN architecture tuning
- Real-time webcam detection system

---

## 📦 Installation

Install dependencies:

pip install -r requirements.txt