# AI & ML Internship - Task 1: Data Cleaning & Preprocessing

## Objective

The objective of this task is to clean and prepare raw data for machine learning.

## Dataset

The **Titanic Dataset** was used for this task.

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Kaggle Notebook

## Tasks Performed

### 1. Dataset Exploration

The dataset was imported and explored using:

* `df.head()`
* `df.shape`
* `df.info()`
* `df.describe()`
* `df.isnull().sum()`

The dataset contains information such as passenger class, gender, age, fare, family members, survival status, and embarkation details.

### 2. Handling Missing Values

The following missing values were identified:

* `Age` - 177 missing values
* `Cabin` - 687 missing values
* `Embarked` - 2 missing values

Missing values were handled as follows:

* Missing `Age` values were filled using the **median**.
* Missing `Embarked` values were filled using the **mode**.
* The `Cabin` column was removed because it contained a large number of missing values.

After preprocessing, no missing values remained in the dataset.

### 3. Encoding Categorical Features

Categorical variables were converted into numerical form:

* `Sex`

  * Male → 0
  * Female → 1
* `Embarked` was converted using **one-hot encoding**.

### 4. Removing Unnecessary Columns

The following columns were removed:

* `Cabin`
* `Name`
* `Ticket`

These columns were either highly incomplete or text-based features not required for this basic preprocessing task.

### 5. Feature Standardization

The following numerical features were standardized using `StandardScaler`:

* `Age`
* `SibSp`
* `Parch`
* `Fare`

Standardization transforms numerical features to approximately:

* Mean = 0
* Standard Deviation = 1

### 6. Outlier Detection

Outliers were visualized using **boxplots** for:

* Age
* SibSp
* Parch
* Fare

### 7. Outlier Removal

Outliers were removed using the **Interquartile Range (IQR) method**.

Results:

* Rows before outlier removal: **891**
* Rows after outlier removal: **561**
* Outliers removed: **330**

## Final Result

The final cleaned dataset:

* Contains **561 records**
* Contains **no missing values**
* Has categorical features converted into numerical form
* Has numerical features standardized
* Has outliers detected and removed

The dataset is now prepared for further machine learning analysis and model development.

## Repository Structure

```text
AI-ML-Internship-Task1-Data-Preprocessing/
│
├── README.md
├── task-1.ipynb
├── cleaned_titanic.csv
└── archive.zip
```

## Conclusion

The Titanic dataset was successfully cleaned and preprocessed for machine learning. Missing values were handled, categorical variables were encoded, unnecessary columns were removed, numerical features were standardized, and outliers were detected and removed using boxplots and the IQR method.
