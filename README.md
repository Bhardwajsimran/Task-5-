# Task-5-
Ai /ml internship 
# Decision Trees and Random Forests

## 🎯 Objective
Train and evaluate Decision Tree and Random Forest classifiers using the Heart Disease dataset. Understand key concepts such as overfitting, tree depth control, feature importance, and cross-validation.

---

## 📊 Dataset
- **Name**: Heart Disease Dataset
- **Source**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Target**: `target` column (0 = no disease, 1 = heart disease)

---

## 🛠️ Tools & Libraries Used
- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (sklearn)

---

## 🚀 Models Implemented

### 🌳 Decision Tree Classifier
- `max_depth=3`
- Plotted and saved as `decision_tree_plot.png`

### 🌲 Random Forest Classifier
- `n_estimators=100`
- Feature importance plotted as `feature_importances.png`

---

## 📈 Evaluation Results

| Model            | Accuracy (Test Set) |
|------------------|---------------------|
| Decision Tree    | ~0.79               |
| Random Forest    | ~0.85               |
| Cross-Val (RF)   | ~0.83 (5-fold CV)   |

---

## 📌 Key Concepts Covered

- Decision Tree structure and visualization
- Information Gain and Entropy
- Overfitting control using `max_depth`
- Random Forest and Bagging
- Feature importance interpretation
- Model comparison and evaluation

---

## 📉 Visual Outputs

### Decision Tree Visualization
![Decision Tree](decision_tree_plot.png)

### Feature Importances from Random Forest
![Feature Importances](feature_importances.png)

---

## 📁 Files Included
- `task5_model.ipynb`: Main Jupyter Notebook
- `decision_tree_plot.png`: Visualization of decision tree
- `feature_importances.png`: Random forest feature importance
- `README.md`: This file
