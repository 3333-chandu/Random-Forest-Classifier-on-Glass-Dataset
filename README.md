# 🌲 Random Forest Classifier on Glass Dataset

## 📖 Overview
This project implements a **Random Forest Classifier** to predict glass types based on their chemical composition.  
It covers the complete **machine learning workflow** — from **exploratory data analysis (EDA)** and **data preprocessing** to **model training**, **evaluation**, and **ensemble methods** comparison.

---

## 🎯 Objective
To apply and evaluate the **Random Forest algorithm** on the Glass dataset, understand its performance, and explore **Bagging** and **Boosting** ensemble methods for comparison.

---

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Analyzed the structure of the dataset  
- Checked for missing values, outliers, and inconsistencies  
- Explored feature distributions and correlations  

### 2. Data Visualization
- Created histograms, boxplots, and pair plots  
- Visualized relationships between chemical components  
- Identified class separability patterns  

### 3. Data Preprocessing
- Handled missing values using imputation or removal strategies  
- Applied **one-hot encoding** for categorical features (if any)  
- Performed **feature scaling** using standardization or normalization  
- Addressed **class imbalance** using appropriate techniques (e.g., SMOTE or class weights)

### 4. Random Forest Model Implementation
- Split data into **training and testing** sets  
- Implemented **Random Forest Classifier** using `scikit-learn`  
- Evaluated model performance using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  

### 5. Bagging and Boosting Methods
- Implemented **Bagging** (Bootstrap Aggregation) and **Boosting** (e.g., AdaBoost, Gradient Boosting)  
- Compared performance with the base Random Forest model  
- Discussed differences between bagging and boosting approaches  

---

## ⚙️ Tech Stack
| Category | Tools Used |
|-----------|-------------|
| Programming Language | Python |
| Libraries | `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn` |
| Environment | Jupyter Notebook / VS Code |

---

## 📈 Results & Insights
- Random Forest outperformed individual decision trees by reducing overfitting  
- Boosting improved accuracy slightly but required careful parameter tuning  
- Learned how ensemble methods combine multiple weak learners to create strong models  

---

## 📁 Repository Structure
