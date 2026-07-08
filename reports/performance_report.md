# Performance Evaluation Report

## Image Classification using Convolutional Neural Network (CNN)

**Intern:** Atif Rameez

**Internship:** EncoderX AI/ML Internship

**Task:** Week 01 – Image Classification Model

**Framework:** TensorFlow / Keras

**Dataset:** MNIST

---

# Project Objective

The objective of this project was to build an image classification model capable of recognizing handwritten digits using a Convolutional Neural Network (CNN). The project covers the complete workflow of an image classification system, including data preprocessing, model development, training, evaluation, and result analysis.

---

# Dataset

The MNIST dataset was used for this project.

| Property | Value |
|----------|-------|
| Dataset | MNIST |
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Classes | 10 |
| Image Size | 28 × 28 pixels |
| Image Type | Grayscale |

The dataset contains handwritten digits ranging from **0 to 9** and is widely used for image classification tasks.

---

# Data Preprocessing

The following preprocessing steps were performed before training the model:

- Loaded the MNIST dataset.
- Normalized pixel values from **0–255** to **0–1**.
- Reshaped images to `(28, 28, 1)` for CNN input.
- Converted class labels into one-hot encoded vectors.

These preprocessing steps help improve model performance and training efficiency.

---

# Model Architecture

The Convolutional Neural Network consists of the following layers:

| Layer | Description |
|--------|-------------|
| Conv2D | 32 filters with ReLU activation |
| MaxPooling2D | Reduces spatial dimensions |
| Conv2D | 64 filters with ReLU activation |
| MaxPooling2D | Feature downsampling |
| Flatten | Converts feature maps into a vector |
| Dense | 128 neurons with ReLU activation |
| Dropout | 0.3 dropout rate to reduce overfitting |
| Dense | 10 output neurons with Softmax activation |

---

# Training Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |
| Epochs | 5 |
| Batch Size | 32 |
| Validation Split | 20% |

The model was trained using the Adam optimizer and monitored using training accuracy, validation accuracy, training loss, and validation loss.

---

# Evaluation Metrics

The trained model was evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a comprehensive evaluation of the model's classification performance.

---

# Results

The model achieved approximately **99% testing accuracy** on the MNIST dataset.

The training and validation accuracy increased consistently throughout the training process, while the loss decreased steadily, indicating successful learning.

The confusion matrix showed that the majority of handwritten digits were classified correctly with only a few misclassifications.

---

# Result Analysis

The CNN performed well in recognizing handwritten digits due to the effectiveness of convolutional layers in extracting image features.

The training and validation curves remained close to each other, indicating minimal overfitting and good generalization on unseen data.

Most classification errors occurred between digits with similar handwriting patterns.

---

# Future Improvements

The following improvements can further enhance model performance:

- Train the model for more epochs.
- Apply data augmentation techniques.
- Experiment with deeper CNN architectures.
- Tune hyperparameters such as learning rate and batch size.
- Compare CNN performance with transfer learning models on larger datasets.

---

# Conclusion

This project successfully implemented an image classification system using a Convolutional Neural Network.

The model demonstrated excellent performance on the MNIST dataset while satisfying all project objectives, including data preprocessing, CNN implementation, model training, evaluation, and result analysis.

This project also strengthened practical knowledge of TensorFlow, Keras, Computer Vision, and Deep Learning.

---

# Project Files

```
encoderx-image-classification/
│
├── notebook/
│   └── image_classification.ipynb
│
├── models/
│   └── mnist_model.keras
│
├── images/
│   ├── accuracy.png
│   ├── loss.png
│   ├── confusion_matrix.png
│   └── predictions.png
│
├── reports/
│   └── performance_report.md
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Tools & Libraries

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Author

**Atif Siyal**

EncoderX AI/ML Internship

Week 01 – Image Classification Model
