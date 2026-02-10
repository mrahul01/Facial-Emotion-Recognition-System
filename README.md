# 🎭 Facial Emotion Recognition System

A deep learning–based real-time facial emotion recognition system built using **TensorFlow, OpenCV, and Convolutional Neural Networks (CNNs)**.  
The model is trained on the **FER2013 dataset** to classify facial expressions into multiple emotion categories and perform live emotion detection using a webcam.

---

## 📌 Features
- Real-time emotion detection using webcam input
- CNN-based multi-class emotion classification
- Trained on FER2013 dataset with data augmentation
- Robust to variations in lighting and facial expressions
- Easy to run on Google Colab and local systems

---

## 🧠 Emotions Detected
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

---

## 🛠️ Tech Stack
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy, Matplotlib**
- **Google Colab**

---

## 📂 Dataset
- **FER2013** (Facial Expression Recognition 2013)
- Grayscale images of size **48×48**
- 7 emotion classes
- Dataset source: Kaggle

> Note: Dataset is not included in the repository due to size constraints.

---

## ⚙️ Project Structure
Facial-Emotion-Recognition/
│
├── train/ # Training dataset
├── test/ # Testing dataset
├── emotion_model.h5 # Trained CNN model
├── train_model.ipynb # Model training notebook
├── emotion_detection.py # emotion detection script
└── README.md
## 🎥 Real-Time Emotion Detection

Run the following command on your local system:

python emotion_detection.py


Press Q to exit the webcam window.

## 📊 Model Performance

Achieved ~70%+ validation accuracy on FER2013 dataset

Performance improved using data augmentation, batch normalization, and dropout

## 📌 Use Cases

Human–Computer Interaction

Mental health monitoring (research-based)

Smart surveillance systems

Emotion-aware applications
