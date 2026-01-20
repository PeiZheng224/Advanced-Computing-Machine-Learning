# Advanced Computing & Machine Learning — Lab Work

This repository contains my lab work and assignments for the course **Advanced Computing and Machine Learning** at UC Berkeley.

---

## Lab 1: Unsupervised Learning & PCA

This lab explores core concepts in unsupervised learning using the classic Iris dataset.  
The main goal is to understand how data preprocessing and dimensionality reduction work in practice.

### Workflow

The notebook follows these major steps:

1. **Data Loading & Inspection**
   - Load the Iris dataset using seaborn
   - Inspect columns and data types
   - Identify numeric vs. non-numeric variables

2. **Exploratory Data Analysis (EDA)**
   - Pairwise scatterplots of original features
   - Visual inspection of potential clustering structure
   - Preliminary assessment of class separability

3. **Feature Standardization**
   - Mean-centering each numeric column
   - Scaling by standard deviation (z-score normalization)
   - Verifying that standardized features have near-zero mean

4. **Principal Component Analysis (PCA)**
   - Fitting PCA using scikit-learn
   - Transforming standardized data into principal components
   - Interpreting explained variance
   - Vi
