# Paria Rezayan
# Dimensionality Reduction Using PCA and LDA for a Classification Task

**Introduction:**
The main objective of this project is to classify breast cancer patients and healthy controls using machine learning techniques. The dataset used in this project can be found on https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra, and contains measurements such as age, BMI, glucose, insulin, and other biomarkers.

**Dataset:**
The dataset consists of 116 rows and 10 columns. The columns contain numerical values, and there are no null values in the dataset.

**Objective:**
The objective of this project is to build a classification model that can accurately distinguish between breast cancer patients and healthy controls. The dataset is preprocessed, and two different dimensionality reduction techniques, PCA and LDA, are applied to identify the most important features.

**Methodology:**
1. Preprocessed the dataset by scaling it and splitting it into training and testing sets
2. Used PCA to identify the most important features in the dataset by transforming the data into a new set of variables
3. Applied logistic regression to the dataset after being condensed using PCA
4. Evaluated the model by calculating various classification metrics such as accuracy, precision, recall, F1 score, and ROC AUC score
5. Used LDA for finding a linear combination of features that best discriminates between different classes
6. Apploed logistic regression to the dataset after being condensed using LDA
7. Evaluated the model by calculating various classification metrics such as accuracy, precision, recall, F1 score, and ROC AUC score
8. Compared the two classification models after PCA (Model 1) and LDA (Model 2)
