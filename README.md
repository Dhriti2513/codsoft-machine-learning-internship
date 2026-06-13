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

Build a deep learning model capable of generating text sequences by learning character-level patterns directly from a training corpus.

### ⚙️ Data Processing & Training Setup

* Extracted and cleaned 50,000+ characters from a machine learning research paper.
* Converted characters into numerical indices for neural network processing.
* Generated fixed-length input sequences using a 50-character context window.
* Trained the model for 1500 epochs using the Adam optimizer and Cross-Entropy Loss.

### 🧠 Model Used

* Character-Level Recurrent Neural Network (RNN)
* Embedding Layer (64 Dimensions)
* 2-Layer Stacked RNN (128 Hidden Units)
* Fully Connected Output Layer

### 📈 Results

| Metric | Value |
|----------|----------|
| Training Epochs | **1500** |
| Sequence Length | **50 Characters** |
| Embedding Dimension | **64** |
| Hidden Units | **128** |

### 💡 Key Learning

This project provided hands-on experience with sequence modeling, character embeddings, recurrent neural networks, and text generation. The trained model successfully learned domain-specific language patterns and generated new text sequences from a given seed prompt.

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
