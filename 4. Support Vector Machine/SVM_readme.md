# "WH" Questions in SVM

## What:

1. **Data Loading and Exploration:**
   - The code loads a dataset named "Loan_Data.csv" using pandas.
   - Basic exploration of the dataset is performed using methods like `info()`, `isnull()`, `shape`, and dropping missing values.

2. **Data Preprocessing:**
   - Text columns are encoded using `LabelEncoder` from `sklearn.preprocessing`.
   - The dataset is split into features (`x`) and the target variable (`y`).
   - Standard scaling is applied to the features using `StandardScaler` from `sklearn.preprocessing`.

3. **Data Visualization:**
   - Scatter plots are created to visualize relationships between 'ApplicantIncome' and 'LoanAmount', and 'CoapplicantIncome' and 'Dependents'.

4. **Model Training and Evaluation:**
   - The code uses SVM for binary classification to predict loan approval status (`Loan_Status`).
   - It splits the dataset into training and testing sets.
   - It applies the SVM model with a radial basis function (RBF) kernel and a linear kernel.
   - Accuracy, confusion matrix, and classification reports are printed and visualized for model evaluation.

## When:
- **Data Loading and Exploration:**
  - Performed at the beginning of the code.
- **Data Preprocessing:**
  - After loading the data and exploring its characteristics.
- **Data Visualization:**
  - After encoding categorical variables, and before scaling the data.
- **Model Training and Evaluation:**
  - After preprocessing the data.

## Where:
- **Data Loading and Exploration:**
  - Loading data from "Loan_Data.csv".
- **Data Preprocessing:**
  - Encoding text columns using `LabelEncoder`.
  - Scaling data using `StandardScaler`.
- **Data Visualization:**
  - Creating scatter plots for visualization.
- **Model Training and Evaluation:**
  - Applying SVM with RBF and linear kernels.
  - Evaluating the model using accuracy, confusion matrix, and classification reports.

## How:
1. **Data Preprocessing:**
   - Encoding categorical features using `LabelEncoder`.
   - Scaling features using `StandardScaler`.

2. **Data Visualization:**
   - Creating scatter plots using Matplotlib.

3. **Model Training and Evaluation:**
   - Splitting data into training and testing sets.
   - Applying SVM models (linear and RBF kernels) using `SVC`.
   - Calculating accuracy and creating confusion matrices and classification reports using `accuracy_score`, `confusion_matrix`, and `classification_report` from `sklearn.metrics`.

In summary, the code demonstrates the application of SVM for a binary classification task (loan approval prediction) after proper data preprocessing and exploration. It evaluates the model performance using accuracy, confusion matrix, and classification reports for both linear and RBF kernels.
