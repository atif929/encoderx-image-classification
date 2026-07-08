# Image Classification using CNN

## Overview

This project is developed as part of the EncoderX AI/ML Internship Week 01 Task.

The goal of this project is to classify handwritten digits using a Convolutional Neural Network (CNN). The model is trained on the MNIST dataset and evaluated using different classification metrics.

---

## Dataset

Dataset: MNIST

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28
- Classes: 10

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Model Architecture

- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Dropout
- Dense (Softmax)

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

The model achieved approximately 99% test accuracy on the MNIST dataset.

---

## Project Structure

```
encoderx-image-classification/
│
├── notebook/
├── models/
├── images/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

Install the required libraries.

```
pip install -r requirements.txt
```

Run the notebook.

```
jupyter notebook
```

Open

```
image_classification.ipynb
```

---

## Author

Atif Siyal

EncoderX AI/ML Internship
