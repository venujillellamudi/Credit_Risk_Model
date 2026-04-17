# Credit Risk Modeling – Machine Learning Project

## 📌 Overview

This project focuses on building a **Credit Risk Prediction Model** using machine learning techniques. The objective is to predict whether a borrower is likely to **default on a loan** based on historical financial and behavioral data.

The project follows a complete **end-to-end ML workflow**, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

This repository was developed as part of a **machine learning learning project** to understand how credit risk models are built in real-world financial systems.

---

## 🎯 Problem Statement

Financial institutions must assess whether a loan applicant is likely to **repay or default**. Incorrect predictions can lead to:

* Financial losses from loan defaults
* Rejecting trustworthy borrowers
* Poor credit risk management

The goal of this project is to build a classification model that predicts the **probability of loan default**.

---

## 📂 Project Structure

```
.
├── credit_risk_model_codebasics.ipynb   # Main Jupyter notebook
├── README.md                            # Project documentation
├── data/                                # Dataset (if included)
├── models/                              # Saved models (optional)
└── requirements.txt                     # Project dependencies
```

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading

* Load the dataset
* Understand features and target variable (`default`)

### 2️⃣ Train-Test Split

The dataset is split into **training and testing sets before EDA** to prevent **data leakage**.

### 3️⃣ Data Cleaning

* Handling missing values
* Removing duplicate records
* Fixing inconsistent values

### 4️⃣ Exploratory Data Analysis (EDA)

* Distribution of target variable
* Feature relationships
* Outlier detection using box plots
* Identifying class imbalance

### 5️⃣ Outlier Handling

Outliers are detected and removed using statistical rules and visualization techniques.

### 6️⃣ Handling Class Imbalance

Since the dataset contains **imbalanced classes**, the **SMOTE (Synthetic Minority Over-sampling Technique)** method is used to balance the dataset.

### 7️⃣ Feature Preparation

* Feature selection
* Data transformation where required

### 8️⃣ Model Training

Multiple machine learning algorithms are used:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

### 9️⃣ Model Evaluation

Models are evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

The best-performing model is selected based on these metrics.

---

## 🧠 Machine Learning Models Used

| Model               | Purpose                                      |
| ------------------- | -------------------------------------------- |
| Logistic Regression | Baseline interpretable model                 |
| Random Forest       | Ensemble model for improved accuracy         |
| XGBoost             | Gradient boosting model for high performance |

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/credit-risk-model.git
cd credit-risk-model
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
jupyter notebook
```

Open:

```
credit_risk_model_codebasics.ipynb
```

---

## 📊 Key Learnings

* Importance of **avoiding data leakage**
* Handling **imbalanced datasets**
* Detecting and removing **outliers**
* Comparing multiple machine learning models
* Evaluating classification models effectively

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Model explainability using SHAP or LIME
* Deploying the model using an API
* Building a credit risk dashboard

---

## 📜 License

This project is for **educational purposes**.

---

