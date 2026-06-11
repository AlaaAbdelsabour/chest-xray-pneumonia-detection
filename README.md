# Chest X-Ray Pneumonia Detection using Deep Learning

This project is part of my Machine Learning and Deep Learning learning journey.

The goal is to build a Convolutional Neural Network (CNN) model that classifies chest X-ray images into three categories:
- Normal
- Bacterial Pneumonia
- Viral Pneumonia

The project is based on the publicly available Chest X-Ray dataset from Kaggle.

---

## 📌 Problem Statement

Pneumonia is a serious lung infection that can be detected using chest X-ray images.

This project aims to automate pneumonia detection using Deep Learning to assist in early diagnosis.

---

## 🧠 Approach

1. Load and preprocess chest X-ray images.
2. Apply data augmentation to improve model generalization.
3. Build a Convolutional Neural Network (CNN) using TensorFlow/Keras.
4. Train the model on the dataset.
5. Evaluate performance on unseen test data.

---

## 🏗️ Model Architecture

A Convolutional Neural Network (CNN) was used to extract spatial features from X-ray images and perform multi-class classification.

---

## 📊 Results

The model was evaluated on the test dataset:

- **Test Accuracy:** 92.11%
- **Test Loss:** 0.2781

---

## 🔍 Key Insight

- The CNN model achieved strong performance in classifying chest X-ray images.
- Data augmentation helped improve model robustness and generalization.
- Deep learning can effectively capture patterns in medical imaging data, making it useful for healthcare applications.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

---

## 🎯 What I Learned

- Building CNN models for image classification
- Working with medical imaging datasets
- Applying data augmentation techniques
- Evaluating deep learning models
- Understanding real-world AI applications in healthcare

---

## 📁 Project Structure

- chest_xray_cnn.ipynb
- requirements.txt
- README.md

---

## 🚀 Future Improvements

- Try transfer learning (e.g., VGG16, ResNet)
- Improve accuracy using hyperparameter tuning
- Deploy the model as a web application or API
- Add confusion matrix and classification report visualization
