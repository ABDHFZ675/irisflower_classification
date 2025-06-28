# 🌸 Iris Flower Classification using Logistic Regression

##  Introduction
This project aims to classify iris flowers into one of three species—**Iris Setosa**, **Iris Versicolor**, or **Iris Virginica**—by analyzing their physical measurements. Leveraging a well-known dataset and using **Logistic Regression**, a classic supervised learning method, the project demonstrates a simple yet effective classification approach in machine learning.

##  Objectives
- Build a predictive classification model using **Logistic Regression**.
- Train and test the model on the **Iris dataset** with 150 entries.
- Evaluate the model’s accuracy in predicting flower species.
- Optionally, generate visualizations to better understand feature relationships and class separability.

## 📊 Dataset Description
The dataset used is the famous **Iris dataset**, which includes 150 data points spread evenly across three species. Each sample includes the following features:

| Feature Name       | Description                     |
|--------------------|---------------------------------|
| Sepal Length (cm)  | Length of the sepal             |
| Sepal Width (cm)   | Width of the sepal              |
| Petal Length (cm)  | Length of the petal             |
| Petal Width (cm)   | Width of the petal              |
| Species            | Category label (target class)   |

Each flower species is encoded numerically as follows:
- `0`: *Iris Setosa*
- `1`: *Iris Versicolor*
- `2`: *Iris Virginica*

The dataset is balanced, with 50 instances of each class.

##  Technologies & Libraries
The model is developed in Python using the Jupyter Notebook environment. Below are the key libraries and their purposes:

| Library               | Functionality                                      |
|-----------------------|----------------------------------------------------|
| `pandas`              | Data loading and manipulation                      |
| `numpy`               | Numerical operations                               |
| `matplotlib.pyplot`   | Plotting and data visualization                    |
| `sklearn.datasets`    | Access to built-in datasets like Iris              |
| `sklearn.model_selection` | Splitting the dataset into train/test sets   |
| `sklearn.linear_model`    | Implementation of Logistic Regression         |
| `sklearn.metrics`     | Model evaluation via metrics like accuracy         |

## 🔧 Step-by-Step Implementation

1. **Import Required Libraries**  
   Load the necessary Python libraries.
   ```python
   import pandas as pd
   import numpy as np
   import matplotlib.pyplot as plt
   from sklearn.datasets import load_iris
   from sklearn.model_selection import train_test_split
   from sklearn.linear_model import LogisticRegression
   from sklearn.metrics import accuracy_score

  ##  Results

- **Accuracy Achieved**: The Logistic Regression model achieved **100% accuracy** on the test dataset, indicating perfect classification performance in this scenario.
- **Model Evaluation**: The model correctly predicted the species of all iris samples in the test set without any misclassifications.
