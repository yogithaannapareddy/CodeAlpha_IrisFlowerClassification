# CodeAlpha - Iris Flower Classification

## Project Overview

This project is part of the CodeAlpha Data Science Internship.

The objective of this project is to classify Iris flowers into three species based on their measurements:

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Scikit-learn

## Dataset

The Iris dataset is loaded using Scikit-learn.

The dataset contains 150 samples and four features:

- Sepal length
- Sepal width
- Petal length
- Petal width

The target classes are:

- Setosa
- Versicolor
- Virginica

## Machine Learning Model

The K-Nearest Neighbors (KNN) classification algorithm is used.

The dataset is divided into:

- 120 training samples
- 30 testing samples

The model uses 3 nearest neighbors.

## Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

### Result

The model achieved:

**Accuracy: 100% on the test split**

Classification performance on the test data:

| Class | Precision | Recall | F1-score |
|---|---:|---:|---:|
| Setosa | 1.00 | 1.00 | 1.00 |
| Versicolor | 1.00 | 1.00 | 1.00 |
| Virginica | 1.00 | 1.00 | 1.00 |

## How to Run

Install Scikit-learn:

```bash
pip install scikit-learn