# 🌸 Iris Species Prediction using SVM

This project uses the **Support Vector Machine (SVM)** algorithm to classify iris flowers into different species based on their physical features. The model is trained on the popular **Iris dataset** and achieves high accuracy in predicting the correct flower class.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-008080?style=flat-square&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-76B900?style=flat-square"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
</p>

---

## 🧠 What is SVM?

**Support Vector Machine (SVM)** is a supervised machine learning algorithm used for classification and regression tasks.  
It works by finding the best hyperplane that separates data points of different classes in a high-dimensional space.

For this project, SVM is used to classify iris flowers into three species:
- **Setosa**
- **Versicolor**
- **Virginica**

---

## 📑 Dataset: Iris

The Iris dataset is a classic dataset in machine learning and statistics. It contains 150 samples of iris flowers, each described by the following 4 features:

| Feature            | Description                |
|--------------------|----------------------------|
| `sepal length`     | in centimeters             |
| `sepal width`      | in centimeters             |
| `petal length`     | in centimeters             |
| `petal width`      | in centimeters             |

The target column is the **species** of the flower.

---

## 🚀 Project Workflow

1. Load the iris dataset from `sklearn.datasets`
2. Visualize data distribution using seaborn pairplots
3. Split the data into training and test sets
4. Train an SVM classifier (`SVC`) with appropriate kernel
5. Predict flower species on test data
6. Evaluate accuracy using classification metrics
7. Visualize decision boundaries

