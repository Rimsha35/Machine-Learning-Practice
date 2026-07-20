# 🤖 Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

# 📖 Overview

This repository documents my **Machine Learning journey**, where I learn the theory, mathematics, implementation, and practical applications of Machine Learning algorithms using Python and Scikit-Learn.

The repository contains detailed notebooks, theory notes, algorithm implementations, evaluation techniques, and real-world projects covering supervised learning, ensemble learning, and future deep learning topics.

Every project follows a complete Machine Learning workflow including:

- Data Collection
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Model Building
- Hyperparameter Tuning
- Model Evaluation
- Performance Comparison
- Model Saving

The repository is continuously updated as I learn new Machine Learning algorithms and build more advanced projects.

---

# 🎯 Learning Objectives

- Build strong Machine Learning fundamentals
- Understand mathematical intuition behind algorithms
- Learn Scikit-Learn professionally
- Perform Exploratory Data Analysis (EDA)
- Handle missing values and outliers
- Apply Feature Engineering techniques
- Optimize models using Hyperparameter Tuning
- Evaluate models using appropriate metrics
- Build end-to-end Machine Learning projects
- Create a professional AI & Machine Learning portfolio

---

# 📂 Repository Structure

```text
Machine-Learning/
│
├── Data/
│   ├── advertising.csv
│   ├── heart.csv
│   ├── insurance_regression.csv
│   └── Breast Cancer Wisconsin (Diagnostic) Data Set.csv
│
├── Linear-Regression/
│   ├── Linear-Regression.ipynb
│   ├── Multiple-Linear-Regression.ipynb
│   ├── Polynomial-Regression.ipynb
│   ├── Polynomial-Regression-Theory.ipynb
│   └── README.md
│
├── Logistic-Regression/
│   ├── Logistic-Regression_Breast_Cancer.ipynb
│   └── README.md
│
├── Decision-Tree/
│   ├── Decision-Tree-Classifier.ipynb
│   ├── Decision-Tree-Regressor.ipynb
│   └── README.md
│
├── Random-Forest/
│   ├── Random-Forest-Classifier.ipynb
│   ├── README.md
│   └── random_forest_fraud.pkl
│
├── Ensembles-Learning/
│   ├── Ensemble-Learning.ipynb
│   └── README.md
│
├── Mini-Projects/
│   ├── Advertising-Sales-Prediction.ipynb
│   ├── House-Price-Prediction.ipynb
│   └── Insurance-Medical-Charges-Prediction.ipynb
│
├── requirements.txt
└── README.md
```

---

# 📚 Topics Covered

## 📈 Regression

- Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Regression Evaluation Metrics
- Regularization Concepts

---

## 🌳 Classification

### Logistic Regression

- Sigmoid Function
- Binary Classification
- Decision Boundary
- Probability Prediction
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC Curve
- ROC-AUC

---

### Decision Tree

- Decision Tree Classifier
- Decision Tree Regressor
- Entropy
- Gini Impurity
- Information Gain
- Feature Importance
- Tree Visualization
- Cross Validation
- Overfitting
- Pre-Pruning
- Post-Pruning

---

### Random Forest

- Ensemble Learning
- Bootstrap Sampling
- Bagging
- Random Feature Selection
- Voting Mechanism
- Out-of-Bag (OOB) Score
- Hyperparameter Tuning
- GridSearchCV
- Stratified K-Fold Cross Validation
- SMOTE
- Threshold Tuning
- Feature Importance
- Model Serialization

---

## 📊 Data Analysis

- Data Cleaning
- Missing Value Handling
- Encoding Techniques
- Feature Engineering
- Feature Scaling
- Correlation Analysis
- Outlier Detection
- Data Visualization

---

## 📈 Model Evaluation

### Regression

- MAE
- MSE
- RMSE
- R² Score

### Classification

- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curve
- ROC-AUC
- Precision-Recall Curve
- Confusion Matrix
- Cross Validation
- Classification Report

---

# 📊 Projects

## 📈 Advertising Sales Prediction

Predict product sales based on advertising expenditure using Linear Regression.

### Skills

- EDA
- Data Cleaning
- Feature Engineering
- Linear Regression
- Model Evaluation

---

## 🏠 Insurance Medical Charges Prediction

Built regression models to estimate insurance medical charges.

### Algorithms

- Linear Regression
- Polynomial Regression
- Decision Tree Regressor

### Skills

- Regression Analysis
- Feature Engineering
- Outlier Analysis
- Model Evaluation

---

## 🌸 Iris Flower Classification

Implemented a Decision Tree Classifier on the Iris dataset.

### Skills

- Decision Tree
- Cross Validation
- Feature Importance
- Visualization

### Performance

| Metric | Score |
|---------|------:|
| Train Accuracy | **100%** |
| Test Accuracy | **100%** |
| Cross Validation | **95.33%** |

---

## 🩺 Breast Cancer Classification

Implemented Logistic Regression for breast cancer diagnosis.

### Skills

- Logistic Regression
- Binary Classification
- ROC Curve
- Classification Report
- Model Evaluation

### Performance

| Metric | Score |
|---------|------:|
| Accuracy | **96%** |
| Precision | **97%** |
| Recall | **91%** |
| F1-Score | **94%** |

---

## 💳 Credit Card Fraud Detection

Developed a complete fraud detection pipeline using a **Random Forest Classifier** on an imbalanced dataset.

### Techniques Used

- Exploratory Data Analysis
- Data Preprocessing
- SMOTE
- Pipeline
- Random Forest
- Hyperparameter Tuning
- GridSearchCV
- Stratified K-Fold Cross Validation
- Threshold Tuning
- Feature Importance
- Model Serialization (Joblib)

### Best Hyperparameters

```python
RandomForestClassifier(
    n_estimators=200,
    max_depth=10,
    min_samples_split=2
)
```

### Performance

| Metric | Score |
|---------|------:|
| Precision | **72%** |
| Recall | **77%** |
| F1-Score | **74%** |
| Cross Validation Recall | **83.6%** |

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Imbalanced-Learn
- Joblib
- Jupyter Notebook

---

# 📂 Datasets

Small datasets are included in this repository.

Large datasets are **not included** because of GitHub's file size limitations.

### Credit Card Fraud Detection

Download the dataset from:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Place the downloaded dataset inside the `Data/` folder before running the notebook.

---

# 🚀 Future Roadmap

## Supervised Learning

- ✅ Linear Regression
- ✅ Multiple Linear Regression
- ✅ Polynomial Regression
- ✅ Logistic Regression
- ✅ Decision Tree
- ✅ Random Forest
- 🔜 Support Vector Machine (SVM)
- 🔜 K-Nearest Neighbors (KNN)
- 🔜 Naive Bayes
- 🔜 AdaBoost
- 🔜 Gradient Boosting
- 🔜 XGBoost
- 🔜 LightGBM
- 🔜 CatBoost

---

## Unsupervised Learning

- 🔜 K-Means Clustering
- 🔜 Hierarchical Clustering
- 🔜 DBSCAN
- 🔜 PCA

---

## Deep Learning

- 🔜 Artificial Neural Networks
- 🔜 CNN
- 🔜 RNN
- 🔜 LSTM
- 🔜 Autoencoders

---

## Generative AI

- 🔜 Transformers
- 🔜 Hugging Face
- 🔜 Large Language Models (LLMs)
- 🔜 Retrieval-Augmented Generation (RAG)
- 🔜 AI Agents

---

# 📈 Repository Progress

| Module | Status |
|-----------------------------------------|-------------|
| Linear Regression | ✅ Completed |
| Multiple Linear Regression | ✅ Completed |
| Polynomial Regression | ✅ Completed |
| Logistic Regression | ✅ Completed |
| Decision Tree Classifier | ✅ Completed |
| Decision Tree Regressor | ✅ Completed |
| Ensemble Learning | ✅ Completed |
| Random Forest Classifier | ✅ Completed |
| Support Vector Machine | 🔜 Planned |
| K-Nearest Neighbors | 🔜 Planned |
| Naive Bayes | 🔜 Planned |
| AdaBoost | 🔜 Planned |
| Gradient Boosting | 🔜 Planned |
| XGBoost | 🔜 Planned |
| LightGBM | 🔜 Planned |
| CatBoost | 🔜 Planned |
| Clustering | 🔜 Planned |
| Deep Learning | 🔜 Planned |
| Generative AI | 🔜 Planned |

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/Rimsha35/Machine-Learning.git
```

Move into the project

```bash
cd Machine-Learning
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 🤝 Contributions

Contributions, suggestions, and feedback are always welcome.

If you have ideas for improving the notebooks or adding new Machine Learning projects, feel free to open an issue or submit a pull request.

---

# 📬 Contact

### GitHub

**https://github.com/Rimsha35**

### LinkedIn

**https://www.linkedin.com/in/rimsha-5362b9216/**

---

# ⭐ Support

If you found this repository useful for learning Machine Learning, consider giving it a ⭐. It helps others discover the project and motivates future updates.

Happy Learning! 🚀
