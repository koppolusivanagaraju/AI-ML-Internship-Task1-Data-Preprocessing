# AI & ML Internship - Task 3: Linear Regression

## Objective

The objective of this task is to implement and understand Simple and Multiple Linear Regression.

## Dataset

For this task, the **Housing Price Prediction Dataset** (`Housing.csv`) was used.

The target variable is:

- `price`

The dataset contains information about different characteristics of houses and their corresponding prices.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle Notebook

## Task Overview

The following steps were performed as part of this task:

1. Imported the required Python libraries.
2. Loaded the Housing dataset.
3. Explored the dataset and checked its structure.
4. Checked for missing values.
5. Generated statistical summaries.
6. Preprocessed categorical variables.
7. Split the dataset into training and testing sets.
8. Implemented Simple Linear Regression.
9. Evaluated the Simple Linear Regression model.
10. Implemented Multiple Linear Regression.
11. Evaluated the Multiple Linear Regression model.
12. Compared the two models.
13. Analyzed regression coefficients.
14. Created regression visualizations.
15. Interpreted the results.

## Data Preprocessing

The dataset contains categorical variables that were converted into numerical form.

The following Yes/No variables were encoded as:

- `yes` → `1`
- `no` → `0`

The encoded columns are:

- `mainroad`
- `guestroom`
- `basement`
- `hotwaterheating`
- `airconditioning`
- `prefarea`

The `furnishingstatus` column was converted using one-hot encoding.

After preprocessing, the dataset was checked to ensure that there were no missing values.

## Train-Test Split

The dataset was divided into training and testing sets using an 80:20 ratio.

- Training data: 80%
- Testing data: 20%
- Random state: 42

The resulting datasets were:

- Training data: `(436, 13)`
- Testing data: `(109, 13)`

## Simple Linear Regression

Simple Linear Regression was implemented using:

- **Independent variable:** `area`
- **Target variable:** `price`

The model was trained using the training data and predictions were generated for the test data.

### Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The Simple Linear Regression results were:

```text
MAE: 1474748.1337969352
MSE: 3675286604768.185
R² Score: 0.27287851871974644
