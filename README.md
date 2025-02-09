# Credit Risk Model

## 📌 Overview

This project focuses on modeling the probability of **credit default** using data from the **Lending Club dataset**. The primary objective is to build a logistic regression model that aligns with **Basel regulatory requirements**, ensuring interpretability through model coefficients.

## 📊 Dataset

- **Source**: Lending Club dataset
- **Type of loans**: Mostly **credit card** and **debt consolidation** loans
- **Target variable**: Binary classification (**default vs. no default**)

## 🔍 Methodology

- **Algorithm**: Logistic Regression (due to Basel interpretability requirements), SVM, XGBoost, Random Forest
- **Features**: Binary-encoded independent variables
- **Data balancing**: Adjusted class weights instead of oversampling/undersampling

## 📈 Model Evaluation

The model's performance is primarily assessed using:

- **AUC: 79%**
- **Kolmogorov-Smirnov: 44%** 
- **Gini coefficient: 58%**

## 📜 License

This project is shared for educational purposes.

## ✍️ Author

- **Maćko Wnuk**

