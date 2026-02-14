**Clinical Genomics Mortality Risk Prediction Prototype** 

**Overview**

This project simulates a clinical-genomic data integration pipeline and implements a 12-month mortality risk prediction prototype using SQL-based relational modeling and machine learning.

The objective is to demonstrate how structured clinical data and high-dimensional gene expression data can be integrated into a predictive risk stratification workflow.

**Business Context**

Early identification of high-risk patients is critical in healthtech environments for:

* Clinical prioritization

* Resource allocation

* Preventive intervention strategies

This prototype simulates a simplified predictive system integrating clinical and genomic features.

**Technical Stack**

* Python

* SQLite

* Pandas

* Scikit-learn

* Logistic Regression

* ROC-AUC evaluation
  

**Data Pipeline**

1. Synthetic dataset generation (clinical + gene expression)

2. Relational database modeling using SQLite

3. SQL JOIN operations for data integration

4. Feature transformation (long → wide pivot)

5. Logistic regression risk modeling

6. Model evaluation using ROC-AUC

**Model Performance**

ROC-AUC: **0.69**

The moderate discriminative performance reflects realistic signal-to-noise conditions often observed in high-dimensional biomedical datasets.

**Disclaimer**

This dataset is fully synthetic and created for educational and methodological demonstration purposes only.
