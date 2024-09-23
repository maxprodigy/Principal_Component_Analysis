# Principal Component Analysis (PCA) Project
This repository contains a Python-based implementation of Principal Component Analysis (PCA), showcasing various steps from standardizing data, performing eigendecomposition on the covariance matrix, and visualizing the results. PCA is a powerful dimensionality reduction tool that allows you to transform high-dimensional data into fewer dimensions while retaining most of the variance in the dataset.

# Table of Contents
- Project Overview
- Features
- Usage
- Explanation of PCA Steps

# Project Overview
This project performs the following tasks:

- Loads a dataset and standardizes it.
- Calculates the covariance matrix.
- Computes the eigenvalues and eigenvectors via eigendecomposition.
- Orders the eigenvalues and eigenvectors based on the importance (variance explained).
- Reduces the dataset to a specified number of principal components.
- Visualizes the explained variance and the reduced dataset.

# Features
- Standardizes the dataset.
- Performs PCA through eigendecomposition of the covariance matrix.
- Explains the variance captured by each principal component.
- Reduces the data to a user-defined number of dimensions.
- Provides clear visualizations of the results.

# Usage/Installation
- Clone the repository:

git clone https://github.com/yourusername/pca-project.git

- Navigate to the project directory:

cd pca-project

- Install the required dependencies:

pip install -r requirements.txt

Dependencies include:
- numpy
- pandas
- scikit-learn
- matplotlib

# Explanation of PCA Steps
1. Standardize the Data: Ensures that all features have a mean of 0 and a standard deviation of 1, necessary for PCA.
2. Covariance Matrix: Captures the relationships (covariance) between different features.
3. Eigendecomposition: Breaks the covariance matrix into eigenvalues (variance explained) and eigenvectors (principal components).
4. Order of Importance: The eigenvalues and their corresponding eigenvectors are sorted by importance, with the highest eigenvalues representing the most variance.
5. Matrix Multiplication: Reduces the original dataset into a new dataset of fewer dimensions, preserving the most important patterns.
