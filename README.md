# Data-Preprocessing
A collection of essential data preprocessing techniques outlier handling, missing value treatment, scaling, normalization, and categorical encoding for reusable data science and machine learning workflows.

## Repository Structure

This repository is organized into separate files/modules, each focusing on a specific preprocessing task to keep the code simple, readable, and reusable.

---

## Outlier Detection and Removal

Four commonly used methods to detect and handle outliers:

1. **Z-Score (Box Plot Method)**
2. **Quantile Method**
3. **Z-Score using SciPy Library**
4. **K-Means Clustering Based Outlier Detection**

---

## Missing Values Handling

Different strategies to handle missing data depending on the dataset and problem type:

1. **Mean, Median, Mode Imputation**
2. **K-Nearest Neighbors (KNN) Imputation**
3. **Regression Imputation**
4. **MICE (Multiple Imputation by Chained Equations)**
5. **Random Forest Imputation**
   
---

## Feature Scaling

Scaling ensures that features contribute equally to model training:

1. **Standard Scaling**
2. **Min-Max Scaler**
3. **Max-Abs Scaler**
4. **Robust Scaler**

---


## Feature Encoding

Techniques used to convert categorical data into numerical format:

1. **Label Encoding**
2. **Ordinal Encoding**
3. **One-Hot Encoding**
4. **Binary Encoding**
5. **Manual Encoding**

These methods help prepare categorical features for machine learning models that require numerical input.

---

## Data Transformation & Normalization

Methods to transform and normalize data distributions:

1. **Unit Form Normalization**
  (Random values scaled between 0 and 1)
2. **L1 Normalization**
  (Sum of each row equals 1)
3. **Log Transformation**
  (Used to normalize skewed data)

---

## Purpose of This Repository

* Practice and reference for **data preprocessing**
* Useful for **students, beginners, and professionals**
* Simple, modular files for easy understanding and reuse
* Can be directly integrated into ML pipelines

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy
  
---
