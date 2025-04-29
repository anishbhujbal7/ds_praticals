# Naïve Bayes Classifier on Iris Dataset

This project implements a **Gaussian Naïve Bayes classification** algorithm using Python to classify flowers from the popular **Iris dataset** into one of three species.

---

## 📊 Dataset Overview

- **Dataset**: `iris.csv`
- **Features**:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- **Target**: `Species` (Iris-setosa, Iris-versicolor, Iris-virginica)

---

## 📈 Workflow

1. Load and preprocess the data
2. Train a Gaussian Naïve Bayes classifier
3. Predict on test data
4. Compute and visualize the **confusion matrix**
5. Evaluate metrics: **Accuracy, Error Rate, Precision, Recall**

---

## 🧪 Evaluation Results

| Metric        | Value |
|---------------|-------|
| Accuracy      | 0.98  |
| Error Rate    | 0.02  |
| Precision     | 0.98  |
| Recall        | 0.97  |

---

## 📦 Requirements

- Python 3.x
- pandas
- seaborn
- scikit-learn
- matplotlib

Install dependencies:

```bash
pip install pandas seaborn scikit-learn matplotlib
