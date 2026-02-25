SCENARIO: Credit Card Fraud Detection

Dataset: Credit Card Fraud Detection Dataset

Link:
https://www.kaggle.com/datasets/kartik2112/fraud-detection

Objective:

   To analyze highly imbalanced credit card transaction data and detect fraudulent activities by applying Principal Component Analysis (PCA) for dimensionality reduction and anomaly visualization.

The aim is to transform high-dimensional financial data into a lower-dimensional space (3D) to clearly observe fraudulent transactions as outliers among legitimate ones.

Problem Background:

Credit card fraud detection is a major challenge in the banking and finance sector because:

Fraudulent transactions represent a very small percentage of total transactions

The dataset is highly imbalanced

Traditional analysis techniques struggle to detect rare events

Financial data is often high-dimensional and complex

This project demonstrates how PCA can simplify complex transaction data and help visualize fraud patterns effectively.

Target Variable:

Class

0 → Legitimate Transaction
1 → Fraudulent Transaction

Input Features:

Time

Amount

Multiple anonymized numerical transaction features

Tasks Performed:

Data Preparation:

Imported required Python libraries (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)

Loaded the dataset into a Pandas DataFrame

Inspected dataset using head(), info(), and describe()

Checked for missing values

Analyzed class imbalance

Separated features and target variable

Applied feature scaling using StandardScaler


PCA Implementation:

Applied Principal Component Analysis

Reduced dataset to 3 principal components

Calculated explained variance ratio

Transformed high-dimensional data into reduced space

Studied how much variance was captured by the principal components


Fraud Analysis:

Visualized legitimate and fraudulent transactions in 3D space

Identified fraud cases as scattered outliers

Observed clustering behavior of legitimate transactions

Interpreted anomaly patterns

Evaluation & Interpretation:


Since PCA is an unsupervised learning technique, evaluation was based on:

Explained variance ratio

Visualization clarity

Separation of fraud cases from dense clusters

Observational anomaly detection

The analysis showed that fraudulent transactions tend to appear farther from dense clusters of normal transactions in reduced-dimensional space.

Visualizations:


3D Scatter Plot (PC1 vs PC2 vs PC3)

Fraud vs Legitimate transaction comparison

Explained Variance Bar Chart

Principal Component distribution plots

Key Insights:

PCA effectively reduced dimensionality while preserving most variance

Fraud transactions appeared as anomalies in 3D visualization

Class imbalance remains a major challenge

PCA alone does not classify fraud but enhances interpretability

Outcome:

The project successfully demonstrated how dimensionality reduction techniques like PCA can simplify complex financial datasets and visually highlight fraudulent transactions.

This experiment builds foundational understanding for advanced fraud detection systems such as Logistic Regression, Random Forest, Isolation Forest, and Deep Learning models.

Technologies Used:

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

