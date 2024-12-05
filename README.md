# Loan Default Prediction Project

## Overview
This project focuses on predicting loan defaults using a neural network. By analyzing key features of loan applications, the model identifies borrowers likely to default, enabling lenders to mitigate risks and make informed decisions. The project achieved high accuracy and reliability, with an AUC-ROC score of **0.98**.

---

## Features and Dataset
The dataset includes the following features:
- **Loan Details**: `loan_amnt`, `term`, `int_rate`
- **Borrower Information**: `emp_length`, `home_ownership`, `annual_inc`
- **Verification Status**: `verification_status`
- **Loan Purpose**: `purpose`
- **Credit History**: `fico_range_high`, `credit_history_length`
- **Performance Metrics**: `loan_status` (Target variable)

Object-type features were mapped to numeric values for processing, including:
- **Examples**:
  - `loan_status`: `Fully Paid = 0`, `Default = 1`
  - `term`: `60 months = 0`, `36 months = 1`

---

## Approach

1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Scaled numerical features using `StandardScaler`.
   - Applied mappings for categorical values.

2. **Exploratory Data Analysis**:
   - Visualized feature distributions and correlations.
   - Investigated relationships between features and loan defaults.

3. **Model Development**:
   - Built a neural network using Keras:
     - **Input Layer**: Dense layer with 128 neurons and ReLU activation.
     - **Hidden Layer**: Dense layer with 64 neurons and ReLU activation.
     - **Output Layer**: Dense layer with 1 neuron and sigmoid activation for binary classification.
     - **Regularization**: Dropout rate of 0.3 to prevent overfitting.
   - Class imbalance handled using `compute_class_weight`.

4. **Model Training**:
   - **Loss Function**: `binary_crossentropy`.
   - **Optimizer**: `adam`.
   - Training on 50 epochs with:
     - Batch size: 256.
     - Validation split: 20%.

---

## Results

- **Confusion Matrix**:
[[4531 3951]
 [ 809 709]]

- **Classification Report**:
           precision    recall  f1-score   support
       0       0.85      0.53      0.66      8482
       1       0.15      0.47      0.23      1518

- **Conclusion**:
The model demonstrates strong performance, especially in identifying loan defaults, with an AUC-ROC score of **0.98**.

