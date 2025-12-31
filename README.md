# Oasis-infobyte-task3
📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Due to the highly imbalanced nature of fraud data, special attention is given to preprocessing, model selection, and evaluation metrics beyond simple accuracy.

The goal is to build a reliable fraud detection system that can distinguish between legitimate and fraudulent transactions effectively.

🎯 Objectives

Analyze and understand credit card transaction data

Handle class imbalance in fraud detection

Build machine learning models for fraud classification

Evaluate model performance using appropriate metrics

Visualize results for better interpretability

📊 Dataset

Dataset Used: Credit Card Fraud Detection Dataset

Contains transactions made by credit cards

Features are anonymized using PCA (V1–V28)

Additional features: Time, Amount

Target column:

Class = 0 → Non-fraudulent transaction

Class = 1 → Fraudulent transaction

The dataset is highly imbalanced, with fraud transactions accounting for a very small percentage of total data.

🛠️ Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Google Colab / Jupyter Notebook

🔍 Methodology
1. Data Loading & Exploration

Loaded the dataset and examined structure and distribution

Identified severe class imbalance

2. Data Preprocessing

Scaled Amount and Time features using StandardScaler

Split the dataset into training and testing sets using stratified sampling

3. Model Building

The following machine learning models were implemented:

Logistic Regression

Random Forest Classifier

To optimize training time, the number of estimators in Random Forest was adjusted.

4. Model Evaluation

Models were evaluated using:

Precision

Recall

F1-score

Confusion Matrix

ROC-AUC Score

These metrics are more suitable than accuracy for imbalanced datasets.

5. Visualization

Class distribution plot

Confusion matrix

ROC curve

Feature importance (Random Forest)

📈 Results

Logistic Regression provided a strong baseline model

Random Forest achieved better performance in detecting fraud cases

ROC-AUC score demonstrated effective separation between fraud and non-fraud transactions

✅ Conclusion

This project demonstrates the effectiveness of machine learning techniques in detecting fraudulent credit card transactions. By handling class imbalance and using appropriate evaluation metrics, the models were able to identify fraud with high reliability. The system can be further enhanced using advanced techniques such as SMOTE or deep learning models.

Author:T.K.Harini

Linkedin: https://www.linkedin.com/posts/harini-t-k-a28289367_oasisinfobyte-oasisinfobytefamily-internship-activity-7412034289980235776-2CUG?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFr80oABbdhnn9yz4_4LyRKHyRanQzrm5JM
