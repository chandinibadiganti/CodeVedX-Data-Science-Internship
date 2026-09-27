# Credit Card Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning.

The model classifies credit card transactions as either genuine or fraudulent based on transaction data.

## 🎯 Objective

The main objective is to build a Machine Learning model that can identify fraudulent transactions and reduce the risk of financial fraud.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 📂 Dataset

The dataset contains credit card transaction information and a target variable called `Class`.

- `0` – Genuine transaction
- `1` – Fraudulent transaction

## 🔧 Data Preprocessing

The following steps were performed:

1. Loaded the credit card transaction dataset.
2. Inspected the dataset.
3. Checked for missing values.
4. Checked for duplicate records.
5. Normalized numerical transaction features.
6. Separated input features and target variable.
7. Split the dataset into training and testing sets.

## ⚖️ Handling Class Imbalance

Credit card fraud datasets are usually highly imbalanced because genuine transactions are much more common than fraudulent transactions.

The `class_weight="balanced"` technique was used with Logistic Regression to give more importance to the minority fraud class.

## 🤖 Machine Learning Model

A **Logistic Regression** classification model was used to classify transactions as genuine or fraudulent.

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

Precision and recall are particularly important for evaluating fraud detection performance.

## 🎯 Final Prediction

The trained model was used to classify a transaction as either genuine or fraudulent.

## 💻 Platform

The project was developed and executed using **Google Colab**.

## 👩‍💻 Internship Task

**CodeVedX Data Science Internship – Task 5**

**Project:** Credit Card Fraud Detection
