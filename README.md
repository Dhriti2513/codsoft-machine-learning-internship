# 🚀 CodSoft Machine Learning Internship

Welcome to my official **CodSoft Machine Learning Internship** project repository. This portfolio focuses on **quality over quantity**, showcasing **three carefully selected projects** that demonstrate progressive expertise across different domains of Machine Learning, from traditional classification models to advanced deep learning architectures.

The selected projects cover:

* 📊 Business Intelligence & Customer Analytics
* 🛡️ Fraud Detection & Imbalanced Classification
* 🤖 Deep Learning & Sequence Modeling

---

# 📂 Project Portfolio Summary

| Project | Domain | Core Algorithm / Framework | Strategic Focus |
|----------|----------|----------|----------|
| **Task 2: Credit Card Fraud Detection** | Risk Analytics & Fraud Detection | Random Forest Classifier | Handling highly imbalanced datasets and detecting fraudulent transactions |
| **Task 3: Bank Customer Churn Prediction** | Business Analytics & Retention Modeling | HistGradientBoosting Classifier | Predicting customer attrition using behavioral and financial data |
| **Task 5: Handwritten Text Generation** | Deep Learning & Sequence Modeling | Character-Level RNN (PyTorch / TensorFlow) | Generating text sequences using recurrent neural networks |

---

# 🛠️ Project Details

## 📑 Task 2: Credit Card Fraud Detection System

### 🎯 Objective

Develop a machine learning model capable of identifying fraudulent financial transactions from a large-scale dataset containing over **550,000 transaction records**.

### ⚙️ Feature Engineering & Data Processing

* Converted customer **Date of Birth (DOB)** into a meaningful **Age** feature.
* Created an **Abnormal Hour Flag** (`is_abnormal_hour`) to identify transactions occurring during late-night hours where fraud probability is historically higher.
* Addressed severe class imbalance (**99.61% legitimate vs 0.38% fraudulent transactions**) using strategic majority-class downsampling.

### 🧠 Model Used

* Random Forest Classifier

### 📈 Performance Metrics

| Metric | Score |
|----------|----------|
| Recall (Fraud Class) | **97%** |
| Precision (Fraud Class) | **96%** |
| ROC-AUC Score | **0.9951** |

### 💡 Key Learning

This project demonstrates the importance of balancing datasets, feature engineering, and optimizing recall in high-risk financial systems where missing fraudulent transactions can be extremely costly.

---

## 📑 Task 3: Bank Customer Churn Prediction Pipeline

### 🎯 Objective

Predict whether a customer is likely to leave a bank based on demographic, financial, and behavioral characteristics.

### ⚙️ Feature Engineering & Data Processing

* Removed irrelevant identifier columns:
  * `CustomerId`
  * `Surname`
  * `RowNumber`

* Encoded categorical variables:
  * Geography
  * Gender

* Utilized efficient ordinal encoding techniques to prepare features for tree-based learning.

### 🧠 Model Used

* HistGradientBoosting Classifier

### 📈 Performance Metrics

| Metric | Score |
|----------|----------|
| Accuracy | **86%** |
| ROC-AUC Score | **0.8591** |
| Precision (Churn Class) | **77%** |

### 💡 Key Learning

This project highlights customer retention analytics and demonstrates how gradient boosting techniques can effectively capture complex behavioral patterns in structured business data.

---

## 📑 Task 5: Character-Level Text Generation Engine

### 🎯 Objective

Build a deep learning model capable of generating text sequences by learning character-level patterns from training data.

### ⚙️ Architecture Highlights

* Character tokenization pipeline converting text into numerical tensor representations.
* Recurrent Neural Network (RNN) architecture capable of learning sequential dependencies.
* Multi-layer hidden state management for capturing long-term context.
* GPU-accelerated training for faster convergence and improved efficiency.

### 🧠 Technologies Used

* PyTorch / TensorFlow
* NumPy
* Python

### 💡 Key Learning

This project introduces sequence modeling and demonstrates how neural networks can learn language structures and generate coherent text based on learned probability distributions.

---

# 🧰 Tech Stack

| Category | Technologies |
|----------|----------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-Learn |
| Deep Learning | PyTorch, TensorFlow |
| Development Environment | Jupyter Notebook, VS Code |

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
````

## 2️⃣ Install Dependencies

```bash
pip install pandas numpy scikit-learn torch tensorflow jupyter
```

## 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook corresponding to the project you wish to explore and run the cells sequentially.

---

# 📁 Repository Structure

```text
CodSoft-ML-Internship/
│
├── Task-2-Credit-Card-Fraud-Detection/
│   ├── notebook.ipynb
│   └── outputs/
│
├── Task-3-Bank-Churn-Prediction/
│   ├── notebook.ipynb
│   └── outputs/
│
├── Task-5-Handwritten-Text-Generation/
│   ├── notebook.ipynb
│   └── outputs/
│
├── .gitignore                      # Configured to exclude heavy local source .csv data files
└── README.md
```

**Note:** Raw dataset files are omitted from the remote repository due to size limitations on GitHub. Please download them directly from the provided task documentation endpoints.

---

# 🎓 Internship Learning Outcomes

Through these projects, I gained practical experience in:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Imbalanced Dataset Handling
* Ensemble Learning Methods
* Gradient Boosting Algorithms
* Deep Learning Fundamentals
* Sequence Modeling with RNNs
* Model Evaluation & Performance Metrics

---

# 🙏 Acknowledgment

I would like to thank **CodSoft** for providing industry-oriented datasets and project opportunities that helped strengthen my practical understanding of Machine Learning and Deep Learning concepts.

---

## 📌 Tags

`#MachineLearning` `#DeepLearning` `#Python` `#DataScience` `#CodSoft` `#Internship` `#ArtificialIntelligence`

```
```
