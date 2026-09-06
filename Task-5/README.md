# AI & ML Internship - Task 5: Decision Trees and Random Forests

## Objective

Learn and implement tree-based machine learning models for classification using Decision Trees and Random Forests.

## Dataset

The **Heart Disease Dataset** was used for this task.

The dataset contains 1025 records and 14 columns.

The target variable is:

- `target`

Where:

- `0` = No Heart Disease
- `1` = Heart Disease

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle Notebook

## Task Requirements

The following activities were performed:

1. Loaded and inspected the Heart Disease dataset.
2. Checked the target variable distribution.
3. Separated features and target.
4. Split the dataset into training and testing sets.
5. Trained a Decision Tree Classifier.
6. Evaluated the Decision Tree using accuracy and classification report.
7. Generated a confusion matrix.
8. Visualized the Decision Tree.
9. Analyzed the effect of tree depth and overfitting.
10. Trained a controlled Decision Tree.
11. Trained a Random Forest Classifier.
12. Compared Decision Tree and Random Forest accuracy.
13. Analyzed Random Forest feature importance.
14. Performed 5-fold cross-validation.
15. Summarized the final model results.

## Dataset Features

The dataset contains the following features:

- age
- sex
- cp
- trestbps
- chol
- fbs
- restecg
- thalach
- exang
- oldpeak
- slope
- ca
- thal

Target:

- target

## Machine Learning Models

### Decision Tree

A Decision Tree Classifier was trained to classify whether a patient has heart disease.

Different tree depths were tested to understand overfitting and model complexity.

### Random Forest

A Random Forest Classifier was trained using multiple decision trees. Its performance was compared with the Decision Tree model.

## Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report
- 5-Fold Cross-Validation

## Feature Importance

Random Forest feature importance was calculated to identify which features contributed most to the classification predictions.

## Conclusion

This task demonstrated how Decision Trees and Random Forests can be used for binary classification. The effect of tree depth and overfitting was analyzed, model performance was compared, important features were identified, and cross-validation was used to obtain a more reliable estimate of model performance.

## Files

- `task-5.ipynb` - Complete Kaggle notebook containing the implementation, visualizations, model evaluation, and results.
- `README.md` - Documentation for Task 5.
