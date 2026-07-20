# 🍷 K-Nearest Neighbors (KNN) - Wine Classification

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-KNN-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)

</p>

---

## 📖 Project Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** classification algorithm using the **Wine Dataset** from Scikit-learn.

The notebook covers the complete machine learning workflow, including:

- Data loading
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature scaling
- Model training
- Model evaluation
- Hyperparameter tuning
- Model serialization using Joblib

---

## 📂 Project Structure

```text
KNN/
│
├── Wine-Classification.ipynb     # Complete KNN implementation
├── knn_wine_model.pkl            # Trained KNN model
├── wine_scaler.pkl               # Saved StandardScaler
└── README.md
```

---

## 📊 Dataset Information

The project uses the **Wine Dataset** available in **Scikit-learn**.

| Property | Value |
|----------|-------|
| Dataset | Wine |
| Task | Multiclass Classification |
| Samples | 178 |
| Features | 13 |
| Classes | 3 |
| Missing Values | No |

Target Classes:

- Class 0
- Class 1
- Class 2

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📚 Machine Learning Workflow

```text
Load Dataset
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Train-Test Split
      │
      ▼
Feature Scaling (StandardScaler)
      │
      ▼
Train KNN Model
      │
      ▼
Model Prediction
      │
      ▼
Performance Evaluation
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Save Model & Scaler
```

---

## ⚙️ Algorithms & Techniques

- K-Nearest Neighbors (KNN)
- StandardScaler
- Euclidean Distance
- Hyperparameter Tuning
- Model Serialization

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## 💾 Saved Files

### Trained Model

```text
knn_wine_model.pkl
```

Contains the trained KNN classifier.

---

### Feature Scaler

```text
wine_scaler.pkl
```

Contains the fitted `StandardScaler` used during training.

> **Note:** The scaler must always be loaded before making predictions on new data.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Rimsha35/Machine-Learning-Practice.git
```

### 2. Navigate to the Project

```bash
cd Machine-Learning-Practice/KNN
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib
```

### 4. Open the Notebook

```bash
jupyter notebook Wine-Classification.ipynb
```

---

## 📂 Repository Files

| File | Description |
|------|-------------|
| `Wine-Classification.ipynb` | Complete KNN workflow |
| `knn_wine_model.pkl` | Trained KNN model |
| `wine_scaler.pkl` | Saved feature scaler |

---

## 📌 Learning Outcomes

After completing this project, you will understand:

- Distance-based machine learning algorithms
- KNN classification
- Feature scaling
- Train-test splitting
- Hyperparameter tuning
- Confusion matrix interpretation
- Model persistence using Joblib
- Predicting on unseen data

---

## 🔮 Future Improvements

- GridSearchCV for automatic hyperparameter tuning
- Cross-validation
- Decision Boundary Visualization
- Flask/FastAPI deployment
- Streamlit web application
- Performance comparison with SVM, Decision Tree, and Random Forest

---

## 👩‍💻 Author

**Rimsha**

- 💼 AI Engineer
- 🌐 GitHub: https://github.com/Rimsha35

---

⭐ If you found this project helpful, consider giving the repository a **Star**!