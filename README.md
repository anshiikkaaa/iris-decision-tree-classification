# Iris Classification using Decision Tree (with Feature Engineering)

## Project Overview

This project applies a **Decision Tree Classifier** to the Iris dataset to classify flower species. It also includes **feature engineering, model evaluation, and feature importance analysis** to improve interpretability and performance.

---

## Dataset

* Dataset: Iris Dataset (from sklearn)

* Features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

* Target Classes:

  * 0 → Setosa
  * 1 → Versicolor
  * 2 → Virginica

---

## Workflow

1. Data Loading and Exploration
2. Data Visualization (class separation)
3. Feature Engineering (derived features)
4. Train-Test Split
5. Decision Tree Model Training
6. Cross-Validation
7. Model Evaluation
8. Feature Importance Analysis
9. Tree Visualization

---

## Machine Learning Model

* Algorithm: Decision Tree Classifier
* Criterion: Gini Index
* Hyperparameter Control: `max_depth` (to reduce overfitting)

---

## Results

* High classification accuracy on test data
* Clear decision boundaries learned by the model
* Feature importance shows which features influence predictions most

---

## Key Visualizations

* Sepal length vs width scatter plot
* Decision tree structure
* Feature importance bar chart

---

## Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## Key Learnings

* Feature engineering improves model performance
* Decision Trees are highly interpretable ML models
* Overfitting control using `max_depth`
* Importance of visualization in classification tasks

---

## Project File

* `iris-classification-decision-tree-feature-engineering.ipynb`
