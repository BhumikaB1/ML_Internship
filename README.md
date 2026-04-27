# Machine Learning Projects: Classification & Regression

This repository contains two end-to-end machine learning projects developed as part of practical AI/ML learning. The focus is on understanding core concepts such as data preprocessing, model training, evaluation, and visualization.

---

##  Overview

This repository demonstrates:

* Supervised Learning (Classification & Regression)
* Data Analysis & Visualization
* Model Evaluation Techniques
* Hands-on implementation using real datasets

---

## 🌸 Project 1: Iris Flower Classification

###  Objective

To classify iris flowers into three species based on sepal and petal measurements:

* Setosa
* Versicolor
* Virginica

###  Approach

* Loaded dataset using `sklearn`
* Performed exploratory data analysis using Seaborn
* Split dataset into training and testing sets
* Trained a **Logistic Regression** model

###  Evaluation

* Accuracy Score
* Confusion Matrix

###  Key Insight

The model performs exceptionally well due to clear separability between classes, especially for Setosa.

---

## 🏠 Project 2: House Price Prediction

###  Objective

To predict house prices based on numerical features such as income, location, and housing attributes.

###  Approach

* Used California Housing dataset
* Handled preprocessing and feature selection
* Applied **Linear Regression** model
* Split data into training and testing sets

###  Evaluation

* Mean Squared Error (MSE)
* Actual vs Predicted visualization

###  Key Insight

Linear Regression provides a good baseline, but performance can be improved using more advanced models.

---

##  Tech Stack

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Project Structure

```
ML-Internship-Tasks/
│
├── 01_Iris_Classification.ipynb
├── 02_House_Price_Prediction.ipynb
├── requirements.txt
└── README.md
```

---

##  How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/ML-Internship-Tasks.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```
jupyter notebook
```

4. Open and run the notebooks step by step.

---

##  Results Summary

| Project                | Model               | Performance Metric |
| ---------------------- | ------------------- | ------------------ |
| Iris Classification    | Logistic Regression | High Accuracy      |
| House Price Prediction | Linear Regression   | Low MSE            |

---

##  Future Improvements

* Implement advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Add feature engineering
* Deploy models using a web interface (Flask/Streamlit)

---

##  What I Learned

* Practical implementation of ML workflows
* Importance of data visualization
* Model evaluation and interpretation
* Difference between classification and regression problems

---

##  Author

**Bhumika Patrange**

---

## ⭐ If you found this useful, consider giving it a star!
