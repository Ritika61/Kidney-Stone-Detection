# Kidney Stone Detection Using Deep Learning

## Project Overview

Kidney stone disease is a common medical condition that affects millions of people worldwide. Early detection is important to prevent complications and improve treatment outcomes.

This project implements a Deep Learning-based Kidney Stone Detection System that automatically classifies medical images as either containing kidney stones or normal findings. The model is trained using a labeled image dataset and evaluated using standard performance metrics.

The objective of this project is to demonstrate how Artificial Intelligence and Computer Vision can assist healthcare professionals in diagnosing kidney stone conditions more efficiently.

---

## Features

- Automated kidney stone detection from medical images
- Deep learning image classification model
- Image preprocessing and normalization
- Model training and validation
- Performance evaluation using accuracy metrics
- Visualization of training and validation results
- Prediction on unseen test images

---

## Dataset

The dataset consists of kidney stone and normal medical images organized into:

```
train/
valid/
test/
```

### Classes

- Kidney Stone
- Normal

Due to GitHub file size limitations, the complete dataset is not included in this repository.

---

## Technologies Used

### Programming Language
- Python

### Libraries and Frameworks
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
Medical image dataset containing kidney stone and normal images.

### 2. Data Preprocessing
- Image resizing
- Normalization
- Data augmentation
- Dataset splitting

### 3. Model Development
A Convolutional Neural Network (CNN) model is developed to learn image patterns associated with kidney stones.

### 4. Model Training
The model is trained using the training dataset and validated using the validation dataset.

### 5. Model Evaluation
Performance is evaluated using:
- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

### 6. Prediction
The trained model predicts whether a new image contains a kidney stone or not.

---

## Repository Structure

```
Kidney-Stone-Detection
│
├── Kidneystonedetection.ipynb
├── README.md
├── requirements.txt
└── images
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Ritika61/Kidney-Stone-Detection.git
```

Move into the project folder:

```bash
cd Kidney-Stone-Detection
```

Install dependencies:

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

---

## Results

The trained deep learning model successfully learned distinguishing features between kidney stone and normal images.

Performance metrics such as training accuracy, validation accuracy, loss curves, and prediction outputs can be observed within the notebook.

---

## Future Improvements

- Deploy as a web application
- Deploy using Flask or Streamlit
- Improve model accuracy with larger datasets
- Add support for CT scan image analysis
- Integrate explainable AI techniques
- Develop a real-time diagnostic system

---

## Author

**Ritika Poudel**

GitHub: https://github.com/Ritika61

---

## Disclaimer

This project is developed for educational and research purposes only. It should not be used as a replacement for professional medical diagnosis.
