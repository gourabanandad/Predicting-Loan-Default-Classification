# Loan Default Classification

## Overview
This project aims to predict loan defaults using machine learning. By analyzing key features of loan applications, the model identifies borrowers likely to default, helping lenders mitigate risks and make informed decisions.

## Dataset
- **Source:** [[Dataset Link (If public, add the link)](https://www.kaggle.com/datasets/wordsforthewise/lending-club)]
- **Description:** The dataset contains information such as credit score, income, loan amount, and other financial indicators.

## Methodology
1. **Data Preprocessing:**
   - Handling missing values
   - Feature encoding
   - Normalization & scaling
2. **Modeling:**
   - Algorithms used: Logistic Regression, Random Forest, XGBoost
   - Hyperparameter tuning
3. **Evaluation:**
   - Metrics: Accuracy, AUC-ROC, Precision-Recall
   - Best Model: XGBoost (AUC-ROC: 0.89)

## Results
- The model achieved **89% accuracy** in predicting loan defaults.
- Feature importance analysis showed that **credit score** is the most significant predictor.

## Usage
To run this project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/gourabanandad/Predicting-Loan-Default-Classification.git
   cd Predicting-Loan-Default-Classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/predicting_loan_default.ipynb
   ```

## Future Work
- Experiment with deep learning models.
- Improve feature engineering.
- Deploy the model as a web application using Flask or Streamlit.

## Contributing
Feel free to fork this project, open issues, or submit pull requests.

## License
[Specify the license, if any]

