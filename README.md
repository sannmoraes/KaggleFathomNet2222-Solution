# 🧠 Handwritten Digit Recognition using Convolutional Neural Networks

A Deep Learning project developed in Python to recognize handwritten digits (0–9) using a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras.

The project performs the complete machine learning workflow, including data loading, preprocessing, exploratory analysis, model training, validation, and prediction generation.

---

## 📌 Project Overview

This project uses the **MNIST handwritten digit dataset** (Kaggle Digit Recognizer format) to train a Convolutional Neural Network capable of classifying grayscale images of handwritten numbers.

The implementation was developed in **Google Colab** using Python and follows the standard deep learning pipeline for image classification.

---

## 🚀 Features

- Dataset loading from CSV files
- Exploratory Data Analysis (EDA)
- Missing value verification
- Image normalization
- Image reshaping (28×28 pixels)
- One-hot encoding of labels
- Training/Validation split
- Convolutional Neural Network (CNN)
- Model training with Keras
- Validation and performance evaluation
- Prediction generation for test images

---

## 🛠 Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📂 Project Structure

```
.
├── Untitled10.ipynb      # Main notebook
├── untitled10.py         # Python version of the notebook
├── link base.txt         # Dataset download link
└── link video.txt        # Project presentation/demo
```

---

## 📊 Dataset

The project expects two CSV files:

- **train.csv**
- **test.csv**

The training dataset contains:

- `label` column (target)
- 784 pixel values representing a **28 × 28 grayscale image**

The images are normalized to improve CNN training performance.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Checking missing values
- Pixel normalization (`0–255 → 0–1`)
- Image reshaping to:

```python
28 × 28 × 1
```

- One-hot encoding of labels
- Training/validation split (90% / 10%)

---

## 🧠 CNN Architecture

The model is implemented using Keras Sequential API and includes convolutional layers for automatic feature extraction from handwritten digits.

Typical components include:

- Convolutional Layers
- Max Pooling
- Dropout
- Fully Connected Layers
- Softmax Output Layer

---

## 📈 Model Workflow

1. Load dataset
2. Explore data
3. Normalize images
4. Reshape images
5. Encode labels
6. Split training/validation data
7. Train CNN
8. Evaluate performance
9. Predict test images

---

## ▶️ Running the Project

### Clone the repository

```bash
git clone https://github.com/your-username/handwritten-digit-recognition.git
```

### Install dependencies

```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
```

### Open

```
Untitled10.ipynb
```

or execute

```bash
python untitled10.py
```

---

## 📷 Example Input

A handwritten grayscale image:

```
28 × 28 pixels
```

↓

CNN

↓

Predicted digit:

```
7
```

---

## 📚 Learning Objectives

This project demonstrates practical knowledge of:

- Computer Vision
- Image Classification
- Convolutional Neural Networks
- Deep Learning
- TensorFlow/Keras
- Data Preprocessing
- Model Evaluation

---

## 🎥 Project Presentation

The repository includes a presentation/demo video referenced in:

```
link video.txt
```

---

## 📥 Dataset Download

The dataset download link is provided in:

```
link base.txt
```

---

## 📄 License

This project was developed for educational purposes and is available for study and learning.
