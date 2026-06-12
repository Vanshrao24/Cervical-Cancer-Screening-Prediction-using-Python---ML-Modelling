# Cervical Cancer Screening Prediction using Python

**Author:** Vansh Rao

A machine learning project to predict cervical cancer screening results using classification algorithms (SVM & KNN) on the Kaggle cervical cancer risk factors dataset.

## Dataset
`kag_risk_factors_cervical_cancer.csv`

## Approach
- Data Imputation (mean/mode for missing values)
- Outlier Removal (IQR method)
- Min-Max Normalization
- Dimensionality Reduction (PCA, 15 components)
- SMOTE for class imbalance
- Models: SVM (RBF kernel) and KNN (k=5)
- Targets: Hinselmann, Schiller, Citology, Biopsy
