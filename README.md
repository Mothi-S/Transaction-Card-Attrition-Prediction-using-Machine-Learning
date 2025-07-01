# 🧾 Transaction Card Attrition Prediction

Predicting transaction card attrition using machine learning techniques to help financial institutions reduce churn and increase customer retention.

---

## 📌 Table of Contents

- [📊 Project Overview](#-project-overview)
- [📁 Dataset](#-dataset)
- [🛠️ Methodology](#️-methodology)
- [🧹 Data Preprocessing](#-data-preprocessing)
- [📈 Model Building](#-model-building)
- [🌐 Web Application (Streamlit)](#-web-application-streamlit)
- [📌 Results](#-results)
- [📸 Screenshots](#-screenshots)

---

## 📊 Project Overview

Transaction card attrition is a significant concern for financial institutions. Customers discontinuing their card usage leads to revenue loss and reduced customer loyalty. This project leverages data and machine learning techniques to:

- Predict cardholder attrition
- Help banks proactively retain customers
- Improve overall profitability

---

## 📁 Dataset

- **Source:** Kaggle  
- **Title:** Credit Card Attrition Rate Prediction  
- **Records:** ~17,000  
- **Features:** 11 including:
  - Gender
  - Marital Status
  - Card Category
  - Dependent Count
  - Total Relationship Count
  - Months Inactive in 12 Months
  - Contact Count in 12 Months
  - Total Amount Change
  - Total Transaction Count
  - Total Transaction Change
  - Attrition Flag (Target)

---

## 🛠️ Methodology

1. **Data Collection** from Kaggle
2. **Feature Engineering** – Extracted customer behavior patterns
3. **Model Development**:
   - Baseline: Logistic Regression
   - Others: Decision Tree, Random Forest, Gradient Boosting
4. **Model Evaluation**:
   - Accuracy, Precision, Recall, F1-Score
   - Train-Test Split (80-20)
   - Hyperparameter tuning

---

## 🧹 Data Preprocessing

- **Missing Values** handled by imputation/removal  
- **Outliers** detected and resolved  
- **Feature Scaling** (Normalization) applied  
- **Encoding**: One-hot encoding for categorical features  
- **Exploratory Data Analysis** (EDA) performed to understand feature relationships

---

## 📈 Model Building

- **Primary Model:** Logistic Regression
- **Why?**
  - Interpretable and efficient for binary classification
  - Handles both numerical and categorical features
- **Accuracy:**
  - **Training:** 79.5%
  - **Testing:** 80%

---

## 🌐 Web Application (Streamlit)

Built an interactive web application using **Streamlit**.

### 🔷 Inputs:
- Gender
- Marital Status
- Card Category
- Dependent Count
- Total Relationship Count
- Months Inactive (12 months)
- Contact Count (12 months)
- Total Amount Change
- Total Transaction Count
- Total Transaction Change

### 🔶 Output:
- Predicts whether a customer is likely to **Attrite** or **Continue** using the card.

---

## 📌 Results

- **Model:** Logistic Regression
- **Testing Accuracy:** 80%
- **Outcome:** Successful classification of customers at risk of attrition
- Streamlit app allows real-time prediction

---

## 📸 Screenshots

### 🔹 Streamlit Web App

![Streamlit UI Screenshot](screenshots/streamlit_ui.PNG)
![Streamlit UI Screenshot](screenshots/streamlit_ui2.PNG)


---

