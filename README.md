# ✋ Hand Gesture Recognition

## 📌 Project Overview

This project develops a **Hand Gesture Recognition model** using Python and Machine Learning. The model is designed to identify and classify different hand gestures from image data, demonstrating how computer vision and machine learning can be used for intuitive human-computer interaction.

## 🎯 Objective

* Recognize different hand gestures
* Process and analyze image data
* Train a machine learning classification model
* Predict gestures from new images
* Evaluate model performance

## 🛠️ Technologies Used

* Python
* NumPy
* OpenCV
* Matplotlib
* Scikit-learn
* Google Colab

## 🔄 Project Workflow

```text
Hand Gesture Images
        ↓
Image Preprocessing
        ↓
Resize Images
        ↓
Feature Extraction
        ↓
Train/Test Split
        ↓
Machine Learning Model
        ↓
Gesture Prediction
        ↓
Accuracy Evaluation
```

## ✋ Gesture Classes

The project can classify different gestures such as:

* Palm ✋
* Fist ✊
* Thumb 👍
* L Gesture
* Peace ✌️

## 🧠 Machine Learning

The images are converted into numerical features before training the classification model. The trained model learns patterns from the gesture images and predicts the class of an unseen image.

## 📊 Evaluation

The model performance can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

## 🚀 How to Run

1. Open the notebook in **Google Colab**.
2. Install/import the required Python libraries.
3. Load or generate the gesture image data.
4. Preprocess the images.
5. Split the data into training and testing sets.
6. Train the machine learning model.
7. Test the model with unseen images.
8. Display the predicted gesture and accuracy.

## 📁 Project Structure

```text
Hand-Gesture-Recognition/
│
├── README.md
├── hand_gesture_recognition.ipynb
└── images/
```

## 📌 Dataset

The original task references the **LeapGestRecog** dataset from Kaggle.

[LeapGestRecog Dataset](https://www.kaggle.com/gti-upm/leapgestrecog?utm_source=chatgpt.com)

**Note:** If you are using the dataset-free version, the project uses synthetically generated gesture patterns instead of the Kaggle dataset.

## 👨‍💻 Author

**Sohil Pasha**
