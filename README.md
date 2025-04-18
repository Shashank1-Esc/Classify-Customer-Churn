# 📊 Classify Customer Churn using Logistic Regression

Welcome to the **Customer Churn Classification** project! 🚀  
This project uses **Logistic Regression** to predict whether a customer will **churn** (leave) or **stay** with a telecom company based on their service usage and account details.

---

## 📁 Project Overview

This notebook takes a CSV file with customer data, processes it, and trains a machine learning model to classify churn using **scikit-learn** and **Logistic Regression**. The goal is to help businesses identify customers likely to leave and take action in advance.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas 🐼
- NumPy 🔢
- scikit-learn 🤖
- Matplotlib 📉
- Seaborn 🎨
- Google Colab ☁️

---

## 📌 Steps Followed

### 1. 📥 Upload & Load Data  
- User uploads a CSV file from their local machine.
- `pandas` reads and loads the data.

### 2. 🧹 Data Cleaning & Preprocessing  
- Dropped unnecessary columns (`customerID`).
- Converted `TotalCharges` to numeric.
- Handled missing values.
- Encoded categorical variables using **LabelEncoder**.
- Scaled numerical features using **StandardScaler**.

### 3. 🧪 Train/Test Split  
- Split the dataset into **80% training** and **20% testing** using `train_test_split`.

### 4. 🤖 Model Training  
- Used **Logistic Regression** to train the model.
- Set `max_iter=1000` to ensure convergence.

### 5. 🧾 Model Evaluation  
- Printed:
  - Accuracy ✅
  - Classification Report 📄
  - Confusion Matrix 🔲
- Visualized the Confusion Matrix using `ConfusionMatrixDisplay`.

### 6. 📊 Feature Importance  
- Plotted the **logistic regression coefficients** to visualize feature importance.
- Helps understand which features contribute most to churn.

---

## 📈 Output Samples

### 🔲 Confusion Matrix
Helps us understand the model's performance:

- True Positives ✅
- True Negatives ✅
- False Positives ❌
- False Negatives ❌

### 🧠 Feature Importance
Visual barplot showing which features impact customer churn the most (e.g., `tenure`, `MonthlyCharges`, `Contract`).

---

## 📂 How to Use

1. Clone this repository  
