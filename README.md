# iris-classification-pyspark
Machine Learning Classification using PySpark on Iris Dataset
# Iris Classification using PySpark

## Project Overview

This project applies machine learning classification techniques using PySpark on the Iris flower dataset. It was also required as an Assignment for subject Data Management for Msc. of Data Analytics at UKM for semester 2 2025/2026. The objective is to classify iris flower species based on sepal and petal measurements. Three classification algorithms were implemented and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest

The project demonstrates a complete machine learning workflow including data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## Dataset Description

The Iris dataset is a well-known classification dataset consisting of 150 flower samples categorized into three species:

* Setosa
* Versicolor
* Virginica

### Features

The dataset contains four numerical input features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable is the flower species.

---

## Methodology

The following steps were performed in this project:

1. Data loading and preprocessing using PySpark
2. Label indexing for categorical target conversion
3. Feature vector creation using VectorAssembler
4. Train-test splitting (80% training, 20% testing)
5. Model training using:

   * Logistic Regression
   * Decision Tree Classifier
   * Random Forest Classifier
6. Model evaluation using:

   * Accuracy
   * Precision
   * Recall
   * F1-score
7. Visualization of:

   * Model performance comparison
   * Confusion matrix
   * Feature importance
   * Scatter plots

---

## Results and Key Findings

All models achieved perfect classification performance on the test dataset with:

* Accuracy = 1.0
* Precision = 1.0
* Recall = 1.0
* F1-score = 1.0

Despite identical evaluation metrics, deeper analysis revealed important differences between the models.

### Key Findings

* Random Forest demonstrated the strongest stability and generalization capability due to ensemble learning.
* Logistic Regression provided strong interpretability and simplicity.
* Decision Tree showed higher susceptibility to overfitting despite achieving perfect accuracy on this dataset.
* The Iris dataset is highly separable, which contributed to the excellent classification performance.

---

## Visualizations

---

## Technologies Used

* Python
* PySpark
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Reproducing the Analysis

### Clone the repository

```bash
git clone https://github.com/dmousa75/iris-classification-pyspark.git
```

### Navigate to project folder

```bash
cd iris-classification-pyspark
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file and run all cells.

---

## Author

Developed as a machine learning and PySpark classification project.
