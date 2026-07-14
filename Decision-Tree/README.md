# 🌳 Decision Tree Machine Learning Projects

This folder contains two practical implementations of the Decision Tree algorithm using Scikit-learn:

- 🌸 Decision Tree Classifier (Iris Dataset)
- 💰 Decision Tree Regressor (Medical Cost Personal Dataset)

These projects demonstrate how Decision Trees can be applied to both **classification** and **regression** problems while covering data preprocessing, model training, evaluation, visualization, and feature importance analysis.

---

# 📂 Projects

## 1️⃣ Decision Tree Classifier

### 📌 Objective

Build a Decision Tree Classification model to classify Iris flowers into three different species based on flower measurements.

### 📂 Dataset

- **Dataset:** Iris Dataset
- **Source:** Scikit-learn
- **Samples:** 150
- **Features:** 4
- **Target Classes:** 3

Classes:

- Setosa
- Versicolor
- Virginica

### 📊 Workflow

- Data Exploration (EDA)
- Train-Test Split
- Model Training
- Prediction
- Model Evaluation
- Cross Validation
- Decision Tree Visualization
- Feature Importance

### 📈 Model Performance

| Metric | Score |
|---------|--------|
| Train Accuracy | 100% |
| Test Accuracy | 100% |
| 5-Fold Cross Validation | 95.33% |

> Although the selected train-test split achieved 100% accuracy, cross-validation provides a more realistic estimate of the model's ability to generalize.

---

## 2️⃣ Decision Tree Regressor

### 📌 Objective

Predict individual medical insurance charges using a Decision Tree Regressor based on personal and medical information.

### 📂 Dataset

**Medical Cost Personal Dataset**

Features:

- Age
- Sex
- BMI
- Children
- Smoker
- Region

Target:

- Medical Charges

### 📊 Workflow

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Train-Test Split
- Model Training
- Hyperparameter Tuning using GridSearchCV
- Prediction
- Residual Analysis
- Feature Importance
- Model Evaluation

### 📈 Model Performance

| Metric | Score |
|---------|---------|
| Train R² Score | 0.756 |
| Test R² Score | 0.682 |
| Mean Absolute Error (MAE) | 0.446 |
| Mean Squared Error (MSE) | 0.417 |
| Root Mean Squared Error (RMSE) | 0.646 |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📚 Key Concepts Covered

## Classification

- Decision Tree Classifier
- Gini Impurity
- Entropy
- Information Gain
- Tree Visualization
- Cross Validation
- Feature Importance
- Overfitting
- Model Evaluation

## Regression

- Decision Tree Regressor
- Regression Trees
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Residual Analysis
- Hyperparameter Tuning
- GridSearchCV
- Feature Importance

---

# 🎯 Skills Demonstrated

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Decision Tree Algorithms
- Model Training
- Model Evaluation
- Hyperparameter Optimization
- Cross Validation
- Regression Analysis
- Classification Analysis
- Data Visualization
- Machine Learning using Scikit-learn

---

# 🚀 Future Improvements

- Cost Complexity Pruning
- Compare Gini vs Entropy
- Compare Decision Tree with Random Forest
- Compare with Gradient Boosting
- Compare with XGBoost
- Implement Pipeline
- Perform Feature Selection
- Evaluate additional regression and classification metrics

---

# 📝 Conclusion

These projects provide a comprehensive understanding of Decision Trees for both supervised learning tasks:

- **Decision Tree Classifier** demonstrates multiclass classification using the Iris dataset.
- **Decision Tree Regressor** demonstrates continuous value prediction using the Medical Cost Personal dataset.

Together, they cover the complete machine learning workflow from preprocessing and exploratory data analysis to model evaluation, visualization, feature importance, hyperparameter tuning, and interpretation.

---

# 👨‍💻 Author

**Rimsha**

AI Engineer | Machine Learning Enthusiast

GitHub: https://github.com/Rimsha35
