# 🌳 Decision Tree Classifier on the Iris Dataset

This project demonstrates the implementation of a **Decision Tree Classifier** using the **Iris dataset** from Scikit-learn. The objective is to classify iris flowers into three species: **Setosa**, **Versicolor**, and **Virginica** based on their sepal and petal measurements.

---

## 📌 Project Overview

Decision Trees are one of the most interpretable supervised machine learning algorithms. In this project, I explored the complete workflow of building a Decision Tree model, including:

- Data exploration and preprocessing
- Train-test splitting
- Model training using `DecisionTreeClassifier`
- Model prediction
- Performance evaluation
- Cross-validation
- Decision Tree visualization

---

## 📂 Dataset

- **Dataset:** Iris Dataset
- **Source:** Scikit-learn
- **Samples:** 150
- **Features:** 4
- **Target Classes:** 3

| Class |
|--------|
| Setosa |
| Versicolor |
| Virginica |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Model Performance

| Metric | Score |
|---------|------:|
| Train Accuracy | 100% |
| Test Accuracy | 100% |
| 5-Fold Cross Validation Accuracy | **95.33%** |

Although the model achieved **100% accuracy** on the selected train-test split, **5-fold cross-validation** produced an average accuracy of **95.33%**. This provides a more reliable estimate of the model's ability to generalize to unseen data and demonstrates why cross-validation is an important evaluation technique.

---

## 📈 What I Learned

Through this project, I gained practical experience with:

- Building a Decision Tree Classifier using Scikit-learn.
- Understanding how Decision Trees split data based on feature values.
- Evaluating model performance using train-test accuracy and cross-validation.
- Understanding the importance of model generalization.
- Visualizing and interpreting the structure of a Decision Tree.
- Comparing Gini Impurity and Entropy as splitting criteria.
- Understanding Information Gain and how Decision Trees select the best split.
- Recognizing the concept of overfitting and methods to reduce it.

---

## 📚 Key Concepts Covered

- Decision Tree Classifier
- Supervised Learning
- Classification
- Gini Impurity
- Entropy
- Information Gain
- Tree Visualization
- Feature Importance
- Cross Validation
- Overfitting
- Model Evaluation

---

## 🚀 Future Improvements

- Perform hyperparameter tuning using GridSearchCV.
- Compare Gini and Entropy criteria.
- Implement Cost Complexity Pruning.
- Compare Decision Trees with Random Forest.
- Evaluate additional classification metrics such as Precision, Recall, F1-Score, and ROC-AUC.
- Apply the model to more complex real-world datasets.

---

## 📝 Conclusion

This project provided a strong introduction to **Decision Trees** and demonstrated how they can effectively classify structured data. While a single train-test split resulted in **100% accuracy**, cross-validation showed a more realistic performance of **95.33%**, highlighting the importance of evaluating models on multiple data splits.

The Iris dataset is an excellent starting point for learning Decision Trees because of its simplicity, balanced classes, and well-separated features. This project also builds a solid foundation for studying advanced ensemble algorithms such as **Random Forest**, **Gradient Boosting**, **XGBoost**, **LightGBM**, and **CatBoost**.

---

## 👨‍💻 Author

**Rimsha**  
AI Engineer | Machine Learning Enthusiast