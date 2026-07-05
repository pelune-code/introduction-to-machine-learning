# introduction-to-machine-learning

# Asthma Disease Classification using Python

## Project Overview

This project focuses on developing a machine learning model to classify asthma disease based on patient health data. The objective is to predict whether a patient is likely to have asthma using medical information.

---

## Libraries Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset

The dataset contains patient information including demographic characteristics, medical history, environmental factors, and lifestyle habits. The target variable indicates whether the patient has asthma.

### Example Features

- Age
- Gender
- BMI
- Smoking status
- Family history
- Allergies
- Air pollution exposure
- Physical activity
- Respiratory symptoms

### Target

- **0** – No Asthma
- **1** – Asthma

---

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas.

```python
import pandas as pd

df = pd.read_csv("asthma_disease_data.csv")
```

### 2. Data Preprocessing

The preprocessing stage includes:

- Feature scaling
- Splitting the dataset into training and testing sets
- Balancing classes (has asthma/does not have asthma) using Oversampling and Undersampling

---

### 3. Model Training

Several classification algorithms can be evaluated:

- Decision Tree
- Random Forest
- Naive Bayes

### 4. Model Evaluation

Performance is measured using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Future Improvements

- Hyperparameter optimization using GridSearchCV
- Cross-validation
- Ensemble learning
- Deep learning approaches using TensorFlow or PyTorch

---
