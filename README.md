# Credit Card Fraud Detection System

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset was analyzed, preprocessed, and balanced using **SMOTE (Synthetic Minority Oversampling Technique)** to improve the performance of classification models on imbalanced data.

## Objective
The goal of this project is to build and compare machine learning models for fraud detection and evaluate their performance using multiple classification metrics.And select the most suitable model

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

## Workflow

* Loaded and explored the dataset
* Performed data preprocessing and statistical analysis
* Visualized fraud and normal transaction distributions
* Generated a correlation heatmap
* Balanced the dataset using SMOTE
* Split the data into training and testing sets
* Trained and compared:
  * Logistic Regression
  * Decision Tree Classifier
  * Random Forest Classifier

## Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* ROC-AUC Score
* Matthews Correlation Coefficient (MCC)
* Cohen’s Kappa Score

## Results
The Random Forest model achieved the best overall performance among the implemented models, demonstrating strong capability in identifying fraudulent transactions. The project highlights the importance of handling class imbalance and using multiple evaluation metrics for fraud detection problems.

## Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset is not included in this repository due to its size. Please download it from the link above and place the CSV file in the project directory before running the notebook.

## How to Run
1. Download the dataset.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
   ```
3. Open the Jupyter Notebook or Google Colab notebook.
4. Update the dataset path.
5. Run all cells to reproduce the results.
