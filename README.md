# MNIST Classification Assignment

## Overview
This project focuses on classifying handwritten digits (0–9) from the famous MNIST dataset using Machine Learning techniques in Python.

The notebook demonstrates an end-to-end ML workflow:
- Loading raw MNIST IDX dataset files
- Data preprocessing and normalization
- Exploratory Data Analysis (EDA)
- Data visualization
- Training multiple classification models
- Hyperparameter tuning
- Model evaluation and comparison
- Final performance analysis

---

## Assignment Question

### Q2. Use MNIST Dataset

### (a) Multi-Class Classification
Use the above classifiers to perform multi-class classification where the goal is to classify each image into one of the ten digits:

**0, 1, 2, 3, 4, 5, 6, 7, 8, 9**

### (b) Exploration of Different Evaluation Metrics
Evaluate all models using different evaluation metrics.

### (c) Parameter Tuning through Grid Search / Cross Validation
Tune model parameters using two powerful techniques:

- Grid Search
- Cross Validation

---

## Dataset Information

The MNIST dataset contains grayscale images of handwritten digits.

- Total Classes: 10 (Digits 0 to 9)
- Image Size: 28 × 28 pixels
- Features per image: 784
- Training Samples: 60,000
- Test Samples: 10,000

Each image is represented as pixel intensity values ranging from 0 to 255.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Classifiers Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Naive Bayes
- Support Vector Machine (SVM)
- Neural Network (MLPClassifier)

---

## Workflow

### 1. Data Loading
The raw IDX files are loaded manually using Python's `struct` module.

### 2. Data Preprocessing
- Reshaping images
- Normalization
- Feature scaling
- Label preparation

### 3. Exploratory Data Analysis
- Class distribution
- Sample digit visualization
- Pixel analysis

### 4. Model Training
Train multiple classifiers on the MNIST dataset.

### 5. Hyperparameter Tuning
Use:
- GridSearchCV
- Cross Validation

### 6. Evaluation Metrics
Models are evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC-AUC (if applicable)

---

## Results

The best-performing classifier is selected based on test accuracy and overall evaluation metrics.

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/MNIST-Classification.git
cd MNIST-Classification
