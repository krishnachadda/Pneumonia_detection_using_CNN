# Pneumonia Detection Using a Custom CNN

A deep learning project that classifies chest X-ray images as **Normal** or **Pneumonia** using a custom Convolutional Neural Network (CNN). The model is implemented with TensorFlow/Keras and trained on the Chest X-Ray Images (Pneumonia) dataset from Kaggle.

---

## Project Overview

Pneumonia is a lung infection that can be detected from chest X-ray images. This project demonstrates how a custom CNN can automatically classify X-ray images into two categories:

- Normal
- Pneumonia

The objective is to build an end-to-end image classification pipeline, including preprocessing, model training, evaluation, and prediction.

---

## Dataset

**Dataset:** Chest X-Ray Images (Pneumonia)

Source:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Dataset Structure

```
train/
    NORMAL/
    PNEUMONIA/

test/
    NORMAL/
    PNEUMONIA/

val/
    NORMAL/
    PNEUMONIA/
```

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- OpenCV

---

## Model Architecture

The custom CNN consists of:

- Convolution Layer
- ReLU Activation
- Max Pooling
- Convolution Layer
- Max Pooling
- Convolution Layer
- Max Pooling
- Flatten Layer
- Dense Layer
- Dropout Layer
- Output Layer (Sigmoid)

Loss Function:
- Binary Crossentropy

Optimizer:
- Adam

Evaluation Metric:
- Accuracy

---

## Project Workflow

1. Load the dataset.
2. Preprocess images.
3. Apply data augmentation.
4. Build a custom CNN.
5. Train the model.
6. Validate the model.
7. Evaluate on the test dataset.
8. Generate predictions.

---

## Repository Structure

```
CNN_Assignment/
│
├── Notebook/
│   └── Pneumonia_detection_using_CNN.ipynb
│
├── images/
│
├── models/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository

```bash
[https://github.com/krishnachadda/Pneumonia_detection_using_CNN.git]
```

Install dependencies

```bash
pip install -r requirements.txt
```

Download the dataset from Kaggle and place it inside the project directory.

---

## Running the Project

Open the notebook

```
Notebook/Pneumonia_detection_using_CNN.ipynb
```
Run all cells sequentially to:

- Load data
- Train the model
- Evaluate performance
- Predict new images

---

## Results

After training, the notebook reports:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Loss Curves
- Accuracy Curves
- Confusion Matrix

Replace this section with the actual values obtained after training.

Example:

| Metric | Value |
|---------|-------|
| Training Accuracy | 98.16% |
| Validation Accuracy | 100% |
| Test Accuracy | 92.15% |

---

## Future Improvements

- Train on a larger dataset
- Improve generalization using transfer learning
- Deploy the model as a web application
- Add Grad-CAM visualization
- Support multi-class disease classification

---

## Author

Krishna Chadda

B.Tech (Artificial Intelligence & Machine Learning)

GLA University

