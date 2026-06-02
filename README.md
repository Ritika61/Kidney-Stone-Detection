# Kidney Stone Detection Using Deep Learning

## Project Overview

Kidney stone disease is one of the most common urological disorders worldwide. Early and accurate diagnosis is essential to prevent severe complications such as urinary obstruction, infection, and kidney damage.

This project presents a Deep Learning-based Kidney Stone Detection System developed using Convolutional Neural Networks (CNNs). The model automatically classifies CT scan images into two categories: **Normal** and **Kidney Stone**. The system was trained and evaluated on a publicly available medical imaging dataset and achieved high classification performance.

The project demonstrates the potential of Artificial Intelligence and Computer Vision in supporting healthcare professionals by providing rapid and reliable image-based diagnosis.

---

## Features

* Automated kidney stone detection from CT scan images
* Custom CNN architecture built from scratch
* Image preprocessing and data augmentation
* Training and validation performance monitoring
* Confusion matrix and ROC-AUC evaluation
* Prediction on unseen test images
* Reproducible Jupyter Notebook implementation

---

## Dataset

The dataset consists of CT scan images organized into:

```text
train/
valid/
test/
```

### Classes

* Normal
* Stone

The original dataset was obtained from a publicly available Roboflow medical imaging dataset.

**Note:** The dataset is not included in this repository because GitHub file size limitations prevent uploading the complete dataset.

---

## Technologies Used

### Programming Language

* Python

### Libraries and Frameworks

* TensorFlow
* Keras
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Model Architecture

The proposed CNN architecture consists of:

* Conv2D (32 filters)
* Batch Normalization
* Max Pooling
* Conv2D (64 filters)
* Batch Normalization
* Max Pooling
* Conv2D (128 filters)
* Batch Normalization
* Max Pooling
* Dense Layer (256 neurons)
* Dropout (0.4)
* Softmax Output Layer

The model was trained using:

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Batch Size: 32
* Epochs: 20
* Learning Rate Scheduler: ReduceLROnPlateau

---

## Project Workflow

### 1. Data Collection

CT scan image dataset containing Normal and Stone classes.

### 2. Data Preprocessing

* Image resizing (150×150)
* Pixel normalization
* Data augmentation
* Dataset splitting

### 3. Model Development

A Convolutional Neural Network (CNN) was designed and implemented from scratch using TensorFlow/Keras.

### 4. Model Training

The model was trained using augmented training images and validated using a separate validation set.

### 5. Model Evaluation

Performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve

### 6. Prediction

The trained model predicts whether a CT scan image contains a kidney stone or not.

---

## Results

### Training Accuracy and Loss

![Training Accuracy and Loss](Training%20Accuracy%20%26%20Loss%20Curve.png)

### Confusion Matrix

![Confusion Matrix](Confusion%20Matrix.png)

### Normalized Confusion Matrix

![Normalized Confusion Matrix](Normalized%20Confusion%20Matrix.png)

### Sample Predictions

![Sample Predictions](Sample%20Predictions.png)

### ROC Curve

![ROC Curve](ROC%20Curve.png)

---

## Performance Metrics

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 98.83% |
| Precision | 96.30% |
| Recall    | 98.11% |
| F1-Score  | 97.20% |
| ROC-AUC   | 1.00   |

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Ritika61/Kidney-Stone-Detection.git
```

Navigate into the project folder:

```bash
cd Kidney-Stone-Detection
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Kidneystonedetection.ipynb
```

and run all cells.

---

## Repository Structure

```text
Kidney-Stone-Detection
│
├── Kidneystonedetection.ipynb
├── README.md
├── requirements.txt
├── Confusion Matrix.png
├── Normalized Confusion Matrix.png
├── ROC Curve.png
├── Sample Predictions.png
└── Training Accuracy & Loss Curve.png
```

---

## Future Improvements

* Multi-class kidney abnormality classification
* Kidney stone localization and segmentation
* Explainable AI using Grad-CAM
* Flask or Streamlit web deployment
* Real-time clinical decision support integration
* Larger and more diverse medical datasets

---

## Author

**Ritika Poudel**

GitHub: https://github.com/Ritika61

University of Sunderland

Module: CET313 – Artificial Intelligence

---

## Disclaimer

This project was developed for educational and research purposes only. It is not intended to replace professional medical diagnosis, treatment, or clinical decision-making.
