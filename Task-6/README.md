# AI & ML Internship - Task 6: K-Nearest Neighbors (KNN) Classification

## Objective

The objective of this task is to understand and implement the K-Nearest Neighbors (KNN) algorithm for classification problems.

The task focuses on training a KNN classifier, experimenting with different values of K, evaluating the model, and visualizing its decision boundaries.

## Dataset

For this task, the **Iris Dataset** was used.

The dataset was added to the Kaggle notebook as an input dataset.

The dataset contains information about iris flowers and includes four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable represents the different iris flower species.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle Notebook

## Task Steps

### 1. Load the Dataset

The Iris dataset was loaded into the Kaggle notebook and its structure, column names, data types, and missing values were checked.

### 2. Prepare the Data

The input features were separated from the target variable.

The dataset was prepared for machine learning classification.

### 3. Split the Dataset

The dataset was divided into training and testing sets.

The training data was used to train the KNN model, while the testing data was used to evaluate its performance.

### 4. Normalize the Features

Since KNN is a distance-based algorithm, the numerical features were normalized using `StandardScaler`.

This ensures that features with larger numerical values do not dominate the distance calculation.

### 5. Train the KNN Model

A `KNeighborsClassifier` from Scikit-learn was used to build the classification model.

Different values of K were tested to determine a suitable K value.

### 6. Find the Best K

The model was evaluated using multiple K values.

A graph of K values against classification accuracy was created to help identify the best K value.

### 7. Model Evaluation

The final KNN model was evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

The evaluation helps determine how well the model predicts the classes in the testing dataset.

### 8. Decision Boundary Visualization

The decision boundaries of the KNN classifier were visualized using selected features.

This helps demonstrate how KNN separates different classes based on feature values.

## Key Concepts Learned

- K-Nearest Neighbors classification
- Feature normalization
- Train-test splitting
- Choosing an appropriate K value
- Classification accuracy
- Confusion matrix
- Precision
- Recall
- F1-score
- Decision boundary visualization

## Conclusion

The K-Nearest Neighbors algorithm was successfully implemented for classification using the Iris dataset.

Different K values were tested and the model performance was evaluated using accuracy and a confusion matrix. Feature normalization was performed before training because KNN relies on distance calculations.

The experiment demonstrates how the choice of K can affect classification performance and how visualization can help understand the decision boundaries of a KNN classifier.

## Files

- `task-6.ipynb` - Kaggle notebook containing the complete KNN implementation and analysis.
- `README.md` - Project documentation.

## Author

AI & ML Internship - Task 6
