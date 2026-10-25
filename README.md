# SC5002_Lab_Assignment_1

## Project Overview

This project uses the California Housing Dataset to compare the performance of Linear Regression and Ridge Regression models.

## Dataset used
The dataset is available via the `sklearn.datasets.fetch_california_housing` function in `scikit-learn`.
A subset of **1,000 samples** was randomly selected for simplicity.

---

## Project Structure

### **Task 2.1: Load California Housing Dataset**
- The dataset is loaded using the `fetch_california_housing` function.
- A random sample of 1,000 records is extracted to simplify the experiment.
- Data is standardized, and it is split into training and testing sets.
- The first 5 rows of the dataset are displayed to provide an overview of the data.

---

### **Task 2.2: Train Linear and Ridge Regression Models**
- **Linear Regression**:
  - A 5-fold cross-validation is performed, and the mean \( R^2 \) score is computed to evaluate the model's performance.
- **Ridge Regression**:
  - Ridge Regression is trained with different regularization parameter values (\(\alpha = 0.1\), 10.0, 1000.0).
  - A 5-fold cross-validation process is used to calculate the mean \( R^2 \) score for each value of \(\alpha\), allowing comparison of model performance across different regularization strengths.

---

### **Task 2.3: Visualize Model Performance Comparison**
- A bar chart is created to visually compare the performance of Linear Regression and Ridge Regression with the \( R^2 \) mean scores obtained through cross-validation.

---

