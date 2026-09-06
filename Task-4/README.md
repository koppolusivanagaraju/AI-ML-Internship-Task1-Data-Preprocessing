# AI & ML Internship - Task 4: Classification with Logistic Regression

## Objective

Build a binary classification model using Logistic Regression.

## Dataset

For this task, the **Breast Cancer Wisconsin Dataset** was used.

The dataset is available through the `scikit-learn` library, so no separate dataset file is required.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle Notebook

## Task Overview

The following steps were performed in this task:

1. Selected a binary classification dataset.
2. Loaded and explored the dataset.
3. Checked the dataset structure and target classes.
4. Checked for missing values.
5. Split the data into training and testing sets.
6. Standardized the features using StandardScaler.
7. Built a Logistic Regression model.
8. Trained the model using the training data.
9. Generated predictions and prediction probabilities.
10. Evaluated the model using a confusion matrix.
11. Calculated precision and recall.
12. Calculated the ROC-AUC score.
13. Plotted the ROC curve.
14. Tuned the classification threshold.
15. Compared precision, recall and F1 score at different thresholds.
16. Explained and visualized the sigmoid function.
17. Analyzed Logistic Regression coefficients.

## Dataset Description

The Breast Cancer Wisconsin Dataset is a binary classification dataset containing measurements related to breast cancer tumors.

The target contains two classes:

- `0` - Malignant
- `1` - Benign

The dataset contains 569 samples and 30 numerical features.

The dataset was loaded using:

```python
from sklearn.datasets import load_breast_cancer

cancer = load_breast_cancer()
