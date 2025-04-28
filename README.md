# Basic Machine Learning Algorithm Examples with Scikit-Learn

## Description

This repository contains simple, introductory examples demonstrating the implementation of basic machine learning algorithms using the Python library Scikit-learn. These notebooks are intended for educational purposes to illustrate fundamental concepts.

## Examples Included:

1.  **K-Nearest Neighbors (KNN) Regression Example (`knn_regression_manual_data_example.ipynb`)**
    *   **Algorithm:** `KNeighborsRegressor`
    *   **Data:** Manually entered small dataset (Height, Age, Weight).
    *   **Goal:** Predicts 'Weight' based on 'Height' and 'Age' for a new data point using the 3 nearest neighbors (Manhattan distance). Also shows how to find the neighbors themselves.
    *   *Note: The original filename might have incorrectly suggested classification.*

2.  **Gaussian Naive Bayes Classification Example (`gaussian_naive_bayes_iris_example.ipynb`)**
    *   **Algorithm:** `GaussianNB`
    *   **Data:** Standard Iris dataset (loaded from `sklearn.datasets`).
    *   **Goal:** Classifies Iris flowers into one of three species based on sepal and petal measurements. Evaluates the model using accuracy score.

## Requirements

*   Python 3
*   NumPy
*   Pandas (Used in the KNN example)
*   Scikit-learn
*   Matplotlib (Used implicitly or for potential plotting)

## How to Run

1.  Ensure you have the required libraries installed (`pip install numpy pandas scikit-learn matplotlib`).
2.  Clone this repository.
3.  Run the desired Jupyter Notebook example (`.ipynb` file). The Iris dataset for the Naive Bayes example is loaded automatically by scikit-learn.
