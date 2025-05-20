# 🚀 Loan Default Classification

## 🔍 Overview

This project leverages **machine learning** to predict **loan defaults**, enabling financial institutions to **minimize risk** and make more **data-driven lending decisions**.

By analyzing key financial indicators like **credit score**, **income**, and **loan amount**, the model classifies whether a borrower is likely to default.

---

## 📊 Dataset

* **Source:** [Kaggle - Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
* **Contents:** Includes borrower information such as:

  * Credit score
  * Annual income
  * Loan purpose
  * Debt-to-income ratio
  * Loan amount
  * And more...

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing

* ✅ Missing value treatment
* ✅ Feature encoding
* ✅ Normalization & scaling

### 2️⃣ Modeling

* 💡 Algorithms used:

  * Logistic Regression
  * Random Forest
  * XGBoost
* 🔧 Hyperparameter tuning via GridSearchCV

### 3️⃣ Evaluation

* 📈 Metrics: Accuracy, AUC-ROC, Precision, Recall
* 🏆 Best model: **XGBoost**
* 🎯 AUC-ROC: **0.89**

---

## 📈 Results

* ✅ **Accuracy:** 98%
* 🔍 **Top Feature:** Credit Score — the most powerful predictor of default

---

## 🛠️ How to Use

Clone the repository and get started in minutes:

```bash
git clone https://github.com/gourabanandad/Predicting-Loan-Default-Classification.git
cd Predicting-Loan-Default-Classification
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch the notebook:

```bash
jupyter notebook notebooks/predicting_loan_default.ipynb
```

---

## 🔮 Future Work

* 🤖 Try deep learning models (e.g., neural networks)
* 🧪 Enhance feature engineering
* 🌐 Deploy as a web app using **Flask** or **Streamlit**

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo, open issues, or submit pull requests.

---

## 📄 License

This project is licensed under the **[MIT License](LICENSE)**.

---

Let me know if you'd like a version with badges, emojis removed, or if you want a Markdown file for download.
