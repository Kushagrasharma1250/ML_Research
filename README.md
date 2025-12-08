# ML_research
## 📘 Project Overview
This project presents a **comparative analysis of 30 machine learning models** across multiple algorithmic families, including linear models, regression techniques, support vector machines, tree-based methods, ensemble approaches, naïve Bayes classifiers, k-nearest neighbors, neural networks, and clustering algorithms. The goal is to evaluate their **accuracy, efficiency, and interpretability** under a unified experimental setup, providing insights into trade-offs between model complexity and performance.  

By benchmarking such a wide range of models, the project tests common theoretical assumptions (e.g., ensemble methods outperform individual classifiers, deep learning generalizes better on complex data) and offers practical guidance for model selection in real-world applications.

---

## 📊 Dataset Description
The experiments are conducted on the **UCI Adult Census Income dataset**, a widely used benchmark for classification tasks.  

- **Source:** UCI Machine Learning Repository  
- **Objective:** Predict whether an individual’s income exceeds $50K per year based on demographic and employment attributes.  
- **Size:** ~48,842 records with 14 features and a binary target variable (`<=50K` or `>50K`).  
- **Features:** Age, Workclass, Education, Marital Status, Occupation, Relationship, Race, Sex, Hours-per-week, Capital-gain, Capital-loss, Native Country, etc.  
- **Challenges:**  
  - Class imbalance (~76% earn <=50K, ~24% earn >50K)  
  - Mixed data types (categorical + continuous)  
  - Sensitive attributes (race, sex) raising fairness considerations  

Preprocessing steps include handling missing values, encoding categorical variables, scaling continuous features, and applying cross-validation for robust evaluation.

---

## 🚀 Key Highlights
- Evaluation of **28 diverse ML models** under identical conditions.  
- Metrics: Accuracy, F1-score, ROC-AUC, R², MSE, MAE, Silhouette Score, and training time.  
- Visualizations: Annotated bar plots for classification, regression, unsupervised, and deep learning models.  
- Statistical validation of performance differences.  


## Authors

- [@Kushagrasharma1250](https://github.com/Kushagrasharma1250)

