# Modeling-Imbalanced-Data-A-Sampling-Based-ML-Approach Using SMOTE and Cluster Centroids

**Project Overview**

This project focuses on solving a real-world Imbalanced classification problem. The dataset provided had a significant class imbalance, which negatively affected model performance. To address this, I applied
Data cleaning,Preprocessing, and Balancing techniques using SMOTE (oversampling) and Cluster Centroids (undersampling).

Multiple machine learning models were then trained and evaluated to identify the best-performing model based on the AUROC score.




**Project Objectives**

* Clean and preprocess the dataset
* Handle class imbalance using SMOTE and Cluster Centroids
* Train multiple machine learning models
* Evaluate models using *AUROC* score
* Determine and compare the best-performing model

---

**Data Cleaning & Preprocessing**

Steps include:

* Handling missing values
* Removing duplicate records
* Visualizing class distribution
* Train-test splitting
* Scaling data


---

**Handling Imbalanced Data**

Used the *imbalanced-learn* library.

**SMOTE** (Synthetic Minority Oversampling Technique) : Generates synthetic minority samples to increase representation.

**Cluster Centroids** : Reduces the majority class by replacing clusters with their centroids.

---

**Machine Learning Models Trained**

The following models were used:

* Logistic Regression
* Decision Tree Classifier



Each model was trained on:

*  SMOTE-balanced data
*  Cluster-Centroids-balanced data

---

**Evaluation Metrics**

* AUROC (Area Under the ROC Curve)
* F1-Score


---
**Final Results**

* Balancing the dataset improved the predictive performance significantly
* SMOTE helped improve recall and AUROC
* Cluster Centroids reduced overfitting


The best model (based on AUROC):

      Logistic Regression + SMOTE(BALANCED_DATA)
          F1 Score: 0.09237247084249357
          AUC Score: 0.6079820065952718



---
**Technologies Used**

* Google Colab
* Python
* Pandas / NumPy
* Scikit-Learn
* Imbalanced-Learn (SMOTE & ClusterCentroids)
* Matplotlib / Seaborn

---
**Conclusion**

This project demonstrates how proper data balancing (SMOTE & Cluster Centroids) combined with machine learning models can significantly improve performance on highly imbalanced datasets.
Using Google Colab allowed fast experimentation, visualization, and model comparison.
