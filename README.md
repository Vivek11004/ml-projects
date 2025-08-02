# 🤖 Machine Learning Model Showcase

This repository contains implementations of three fundamental Machine Learning algorithms using Python and scikit-learn, applied on sample datasets to demonstrate data preprocessing, training, evaluation, and visualization.

---

## 📁 Contents

| Notebook | Model | Description |
|----------|-------|-------------|
| [`LinearRegression.ipynb`](./LinearRegression.ipynb) | Linear Regression | Predicts continuous values using a best-fit line |
| [`LogisticRegression.ipynb`](./LogisticRegression.ipynb) | Logistic Regression | Performs binary classification |
| [`DecisionTree.ipynb`](./DecisionTree.ipynb) | Decision Tree Classifier | Creates a tree-based model for classification tasks |

---

## 🧠 Objective

To build a foundational understanding of machine learning models by:
- Preparing datasets (including preprocessing and feature selection)
- Applying appropriate ML algorithms
- Evaluating model performance using metrics
- Visualizing key outputs like confusion matrices and predictions

---

## 📊 Models Overview

### 🔷 1. Linear Regression
- **Goal**: Predict a continuous target variable.
- **Steps**:
  - Load and preprocess the dataset
  - Split into train/test
  - Fit a linear model
  - Visualize predictions
- **Use Case Example**: Predicting house prices based on features.

### 🔷 2. Logistic Regression
- **Goal**: Binary classification (e.g., spam vs. not spam).
- **Steps**:
  - Load binary-labeled data
  - Preprocess and scale features
  - Train and evaluate using accuracy, precision, recall
  - Display confusion matrix
- **Use Case Example**: Customer churn prediction.

### 🔷 3. Decision Tree Classifier
- **Goal**: Multi-class or binary classification.
- **Steps**:
  - Train a decision tree
  - Plot the tree structure
  - Evaluate classification performance
- **Use Case Example**: Classifying types of fruits based on features.

---

## 📦 Dependencies

Install required Python packages via:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
