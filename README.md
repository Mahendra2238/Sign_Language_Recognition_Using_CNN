# ✋ Sign Language Recognition using CNN  

This project implements **Hand Gesture Recognition** using **Convolutional Neural Networks (CNNs)** to classify sign language gestures into numerical categories (0–9).  

---

## 📂 Data Collection  
- `datacollection.py` is used to capture and store training and testing images.  
- Collects **1000 images per gesture** and organizes them into the dataset.  

---

## 📊 Dataset of Hand Gestures  
Different hand gestures correspond to different actions/labels.  

![Hand Gestures](https://github.com/Mahendra2238/Sign_Language_Recognition_Using_CNN/blob/main/imgs/handgest1.jpg)  

---

## 🏗️ Model Training  
- `traingest.py` is used to train the CNN model.  
- After training, **meta** and **index** files are generated, which are later used for prediction.  

CNN Architecture:  
![CNN Architecture](https://github.com/Mahendra2238/Sign_Language_Recognition_Using_CNN/blob/main/imgs/cnnarch1.jpg)  

---

## 🔍 Testing & Prediction  
- `predictgest.py` is used for **real-time gesture prediction**.  
- The model is trained on **10 different gestures (0–9)**.  
- Predictions return the **probability score** for each gesture class.  

Real-time Hand Gesture Prediction:  
![Results](https://github.com/Mahendra2238/Sign_Language_Recognition_Using_CNN/blob/main/imgs/results.jpg)  
![Output](https://github.com/Mahendra2238/Sign_Language_Recognition_Using_CNN/blob/main/imgs/output.png)  

---

## 🚀 Features  
- Real-time hand gesture recognition.  
- Supports 10 numerical gestures (0–9).  
- CNN-based deep learning approach.  
- Easy to extend with additional gestures.  

---

✨ *This project demonstrates the use of CNNs for gesture-based human-computer interaction and can be extended for sign language communication systems.*  
