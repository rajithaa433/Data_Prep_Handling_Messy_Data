# Data_Prep_Handling_Messy_Data

# Customer Data Preprocessing

## Problem Statement
This project focuses on cleaning and preparing a raw customer dataset that contains:
- Missing values
- Duplicate records
- Categorical text data
- Numerical features with different scales

---

## Task 1 — Data Cleaning
- Missing values in **age** were filled using **median**
- Missing values in **city** were filled using **mode**
- Duplicate rows were removed

---

## Task 2 — Encoding
- **City** column → One-Hot Encoding
- **Gender** column → Label Encoding

---

##Task 3 — Feature Scaling
Two scaling techniques were applied:

### 1. Min-Max Scaling
- Scales values between **0 and 1**
- Useful for neural networks and distance-based models

### 2. Standard Scaling
- Centers data around mean = 0 and std = 1
- Works well for models like Logistic Regression and SVM

---

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn

---
