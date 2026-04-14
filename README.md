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

## Machine Learning Models Used

This project may include the following classifiers:

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
- Train/Test split
- Feature scaling / normalization
- Label preparation

### 3. Exploratory Data Analysis
- Class distribution
- Sample digit images
- Pixel statistics

### 4. Model Training
Different ML models are trained on the dataset.

### 5. Hyperparameter Tuning
GridSearchCV / Parameter tuning is used to improve performance.

### 6. Evaluation Metrics
Models are compared using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC-AUC (if applicable)

---

## Results

The best-performing model is selected based on evaluation metrics and test accuracy.

---

## How to Run

### Clone Repository
```bash
git clone https://github.com/your-username/MNIST-Classification.git
cd MNIST-Classification
