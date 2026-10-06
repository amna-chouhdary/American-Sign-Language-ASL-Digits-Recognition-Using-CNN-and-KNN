# American Sign Language (ASL) Digits Recognition

## Project Overview

This project focuses on recognizing American Sign Language (ASL) hand gestures representing digits **0–9** using machine learning and deep learning techniques.

The system takes an image of an ASL hand gesture as input, processes the image, and predicts the corresponding digit.

Two models were implemented and compared:

* K-Nearest Neighbors (KNN)
* Convolutional Neural Network (CNN)

## Models and Results

| Model | Accuracy |
| ----- | -------: |
| KNN   |    95.60%|
| CNN   |    99.6% |

The CNN achieved an accuracy of **99.6%**, while the KNN model achieved **95.60%**.

## Project Workflow

```text
Input Image
     ↓
Image Preprocessing
     ↓
Feature Preparation
     ↓
Model Training
     ↓
Digit Classification
     ↓
Predicted ASL Digit
```

## Classes

The system recognizes the following ASL digit classes:

```text
0  1  2  3  4
5  6  7  8  9
```

## Technologies

* Python
* NumPy
* Pandas
* OpenCV
* Scikit-learn
* TensorFlow
* Keras
* Matplotlib
* Google Colab

## Models

### K-Nearest Neighbors (KNN)

KNN was implemented for ASL digit classification and achieved an accuracy of **95.60%**.

### Convolutional Neural Network (CNN)

CNN was implemented to learn visual patterns from ASL hand-gesture images. It achieved an accuracy of **99.6%**.

## Project Structure

```text
ASL-Digits-Recognition/
│
├── dataset/
├── ASL_Digits_Recognition.ipynb
├── README.md
└── requirements.txt
```

## Future Scope

* Real-time ASL digit recognition
* ASL alphabet recognition
* Word and phrase recognition
* Sign language to text conversion
* Sign language to speech conversion


