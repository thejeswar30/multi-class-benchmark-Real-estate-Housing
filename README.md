# Multi-Class Benchmark Classification Pipeline

## Project Overview

This project implements and compares two supervised machine learning classification algorithms using the Iris dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The Iris dataset contains 150 samples belonging to three species:

* Setosa
* Versicolor
* Virginica

It includes four numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Machine Learning Models

1. Logistic Regression
2. Decision Tree Classifier

## Implementation

* Data loading and exploration
* Exploratory Data Analysis
* Feature scaling using StandardScaler
* 80/20 training and testing split
* Model training and prediction
* Accuracy, Precision, Recall and F1-score evaluation
* Confusion matrix visualization
* Decision boundary visualization using PCA

## Project Structure

```text
Multi_Class_Classification/
├── iris.csv
├── iris_classification.ipynb
├── README.md
└── outputs/
    ├── species_distribution.png
    ├── pairplot.png
    ├── correlation_heatmap.png
    ├── confusion_matrices.png
    └── decision_boundary.png
```

## How to Run

1. Install the required Python libraries.
2. Open the project folder in VS Code.
3. Open `iris_classification.ipynb`.
4. Run all notebook cells.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score

## Outcome

The project demonstrates an end-to-end multi-class classification workflow and compares Logistic Regression and Decision Tree performance.
