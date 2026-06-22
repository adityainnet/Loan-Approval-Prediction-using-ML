# 🏦 Loan Approval Prediction using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4B8BBE?style=for-the-badge">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=for-the-badge&logo=googlecolab">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

# 📌 Project Overview

The **Loan Approval Prediction** project uses **Machine Learning** to predict whether a loan application will be **Approved** or **Rejected** based on an applicant's financial and personal information.

The project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, handling class imbalance, model training, evaluation, and business insights to support data-driven loan approval decisions.

---

# 🎯 Objectives

- 🧹 Data Cleaning & Preprocessing
- 🔍 Exploratory Data Analysis (EDA)
- ⚖️ Handle Class Imbalance using SMOTE
- 🤖 Build Multiple Machine Learning Models
- 📊 Compare Model Performance
- 📈 Identify Important Features
- 💡 Generate Business Insights

---

# 💼 Business Problem

Financial institutions often face two major challenges:

- ❌ Approving loans for applicants who may default.
- ❌ Rejecting applicants who are actually eligible.

This project helps automate the decision-making process by leveraging Machine Learning to improve consistency, reduce risk, and speed up loan approvals.

---

# 📊 Dataset Information

| Attribute | Details |
|------------|---------|
| 📄 Total Records | **614** |
| 📌 Features | **13** |
| 🎯 Target Variable | **Loan_Status** |
| 📂 Dataset Source | Kaggle Loan Approval Prediction Dataset |

### Features Used

- 👤 Gender
- 💍 Married
- 👨‍👩‍👧 Dependents
- 🎓 Education
- 💼 Self Employed
- 💰 Applicant Income
- 🤝 Coapplicant Income
- 🏦 Loan Amount
- ⏳ Loan Amount Term
- ✅ Credit History
- 🏠 Property Area

---

# 🛠 Data Preprocessing

### ✅ Missing Value Handling

- Numerical Features → Median Imputation
- Categorical Features → Mode Imputation

### ✅ Feature Encoding

- Label Encoding for categorical variables

### ✅ Feature Scaling

- StandardScaler for normalization

### ✅ Class Imbalance Handling

- SMOTE (Synthetic Minority Oversampling Technique)

### Dataset Balance

| Before SMOTE | Count |
|--------------|------:|
| Approved | 337 |
| Rejected | 154 |

| After SMOTE | Count |
|-------------|------:|
| Approved | 337 |
| Rejected | 337 |

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented:

- 📈 Logistic Regression
- 🌳 Decision Tree Classifier
- 🌲 Random Forest Classifier

---

# 📈 Model Performance

| Model | Precision | Recall | F1 Score | ROC-AUC |
|-------|----------:|--------:|----------:|---------:|
| Logistic Regression | **0.849** | **0.929** | **0.888** | **0.833** |
| Random Forest | 0.843 | 0.882 | 0.862 | 0.772 |
| Decision Tree | 0.836 | 0.718 | 0.772 | 0.701 |

---

# 🏆 Best Performing Model

### Logistic Regression

### Why?

- ✅ Highest Recall
- ✅ Highest F1 Score
- ✅ Highest ROC-AUC
- ✅ Best Overall Performance

---

# 🔍 Feature Importance

The most influential features affecting loan approval are:

| Feature | Importance |
|----------|-----------:|
| ✅ Credit History | **21.15%** |
| 💰 Applicant Income | **20.35%** |
| 🏦 Loan Amount | **17.52%** |
| 🤝 Coapplicant Income | **10.67%** |
| 🏠 Property Area | **8.46%** |

### Key Insight

Credit History is the strongest factor influencing loan approval decisions.

---

# 📊 Exploratory Data Analysis (EDA)

The project includes the following visualizations:

- 📈 Class Distribution
- 📊 Loan Status Analysis
- 🔥 Correlation Heatmap
- 📉 Confusion Matrix
- 📌 Feature Importance
- 📊 Model Comparison
- 📈 ROC Curve
- 📋 Classification Report

---

# 💡 Business Insights

✔ Applicants with a strong credit history have significantly higher approval chances.

✔ Higher applicant income positively impacts loan approval.

✔ Loan amount plays a crucial role in decision-making.

✔ Property area also influences approval probability.

✔ Balancing datasets using SMOTE improves prediction performance.

---

# 🚀 Tech Stack

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Programming Language |
| 📊 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Computation |
| 📈 Matplotlib | Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 🤖 Scikit-Learn | Machine Learning |
| ⚖️ Imbalanced-Learn (SMOTE) | Class Balancing |
| ☁️ Google Colab | Development Environment |

---

# 📂 Project Structure

```text
Loan-Approval-Prediction/
│
├── Dataset/
│   └── loan_data.csv
│
├── Models/
│   └── loan_approval_model.pkl
│
├── Reports/
│   └── Loan_Approval_Report.pdf
│
├── Images/
│   ├── class_distribution.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   ├── model_comparison.png
│   └── roc_curve.png
│
├── Loan_Approval_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

# 📈 Results

✔ Achieved strong classification performance using Logistic Regression.

✔ Successfully handled missing values, feature encoding, scaling, and class imbalance.

✔ Generated meaningful business insights for loan approval decision-making.

✔ Built an interpretable and reliable machine learning model.

---

# 🚀 Future Improvements

- 🌐 Deploy using Streamlit or Flask
- 📊 Interactive Dashboard with Power BI
- ⚡ Hyperparameter Optimization
- 🧠 XGBoost & LightGBM Implementation
- ☁️ Cloud Deployment (AWS / Azure)

---

# 🎓 Internship Project

This project demonstrates practical experience in:

- ✔ Data Cleaning
- ✔ Exploratory Data Analysis
- ✔ Feature Engineering
- ✔ Class Imbalance Handling
- ✔ Machine Learning Modeling
- ✔ Model Evaluation
- ✔ Business Interpretation

---

# 👨‍💻 Author

### **Aditya Kumar**

**B.Tech - Computer Science & Engineering**

**Vivekananda Global University, Jaipur**

---

<p align="center">
⭐ If you found this project helpful, consider giving it a Star on GitHub!
</p>
