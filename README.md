# 📊 SVM Optimization on UCI HAR Dataset

This repository contains the complete solution for optimizing a **Support Vector Machine (SVM)** classifier on a **multi-class dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones). The project performs parameter tuning using different samples and plots convergence to report the best accuracy achieved.

---

## 🧾 Assignment Brief

- Select a multi-class dataset from UCI with **5,000–30,000 rows**.
- Split the dataset into **10 different 70-30 train-test samples**.
- **Optimize SVM** (kernel, nu) using **100 iterations** per sample.
- Track and report:
  - Best accuracy for each sample.
  - Best kernel and nu values.
  - Convergence plot for the best-performing sample.
- Provide **basic data analytics** and upload the complete result to GitHub.

---

## 📂 Dataset Used

- **Dataset**: Human Activity Recognition (HAR)
- **Rows**: 10,299
- **Classes**: 6
- **Features**: 561

> Dataset Link: [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

---

## 🧠 Techniques Used

- Support Vector Machine (NuSVC)
- Grid Search (manual with `ParameterGrid`)
- Data Normalization (`StandardScaler`)
- 10 Different Train-Test Splits
- Accuracy Tracking and Convergence Plotting
- Exploratory Data Analysis (EDA)

---
## 📈 Results

| Sample | Best Accuracy (%) | Best SVM Parameters           |
|--------|--------------------|-------------------------------|
| S1     | 98.90              | {'kernel': 'rbf', 'nu': 0.01} |
| S2     | 98.80              | {'kernel': 'rbf', 'nu': 0.01} |
| S3     | 98.96              | {'kernel': 'rbf', 'nu': 0.01} |
| S4     | 98.90              | {'kernel': 'rbf', 'nu': 0.01} |
| S5     | 99.00              | {'kernel': 'rbf', 'nu': 0.01} |
| S6     | 98.38              | {'kernel': 'rbf', 'nu': 0.01} |
| S7     | 98.80              | {'kernel': 'rbf', 'nu': 0.01} |
| S8     | 98.90              | {'kernel': 'rbf', 'nu': 0.01} |
| S9     | 98.80              | {'kernel': 'rbf', 'nu': 0.01} |
| S10    | 98.64              | {'kernel': 'poly', 'nu': 0.01} |

> 🔍 The best-performing sample is **S5**, achieving an accuracy of **99.00%** using an **RBF kernel** with **nu = 0.01**.


---
