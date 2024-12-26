# Sports Person Image Classification

## Overview
This project focuses on building an image classification system to identify five prominent sports celebrities using advanced feature extraction and machine learning techniques. The system employs **wavelet transform** for feature engineering, a **CNN classifier** for recognition tasks, and a streamlined **user interface** for seamless interaction.

---

## Objectives
- To classify images of **Maria Sharapova**, **Cristiano Ronaldo**, **Kobe Bryant**, **Novak Djokovic**, and **Virat Kohli**.
- Enhance image recognition performance through **wavelet transform-based feature extraction**.
- Create a user-friendly **web application** for image classification.

---

## Data Collection
- Images of the five sports celebrities were collected using a **custom browser extension** in Google Chrome.
- The dataset was organized into subfolders, each corresponding to a specific celebrity.

---

## Methodology
### 1. **Data Preprocessing**
- **Face Detection & Cropping:** Detected and cropped celebrity faces using OpenCV and Haar cascades.
- **Labeling:** Each cropped image was labeled according to the celebrity.

### 2. **Feature Engineering**
- Used **wavelet transforms** to extract detailed image features.
- Combined wavelet features with raw pixel data for model training.

### 3. **Model Development**
- Employed a **Convolutional Neural Network (CNN)** classifier.
- Optimized hyperparameters using **GridSearchCV**.
- Evaluated performance using metrics like accuracy and confusion matrices.

### 4. **Web Application**
- Built a drag-and-drop interface using **Flask** and **HTML/CSS/JavaScript**.
- Allowed users to upload images and classify them into one of the five categories.

---

## Results
- Achieved high classification accuracy on the validation and test datasets.
- Successfully grouped images into the correct categories for all five sports celebrities.

---

## Features
- **Accurate Classification:** Identifies sports celebrities with high precision.
- **User-Friendly Interface:** Simple drag-and-drop functionality for image uploads.
- **Scalable Design:** The framework can be extended to classify other categories of images.

---

## Tools & Technologies
- **Programming Language:** Python
- **Libraries:** OpenCV, TensorFlow/Keras, NumPy, Scikit-learn
- **Web Framework:** Flask
- **Frontend Technologies:** HTML, CSS, JavaScript

---

## Conclusion
This project demonstrates the application of machine learning and feature engineering techniques in image classification. The developed model and web interface offer a robust solution for classifying sports celebrities, with potential scalability for broader use cases.

---

## Future Scope
- Extend the model to classify additional sports personalities.
- Improve accuracy through advanced neural network architectures.
- Deploy the web application to a cloud service like AWS or Heroku for wider accessibility.

---
