# Enhancing Diabetes Prediction with Binary Classification Models and Support Vector Machines


## Project Summary

This project utilizes the Pima Indians Diabetes dataset to build and evaluate binary classification models for diabetes prediction. The dataset includes 8 medical explanatory variables and one response variable indicating diabetes presence. The models explored are Logistic Regression, K-Nearest Neighbours (KNN), and Linear Discriminant Analysis (LDA). The project also delves into Support Vector Machines (SVM) with a radial basis function (RBF) kernel.

Key components of the project include:

1. **Model Training and Evaluation**:
    - **Logistic Regression**, **KNN**, and **LDA** models were trained and evaluated.
    - Performance metrics such as accuracy, precision, recall, specificity, F1 score, and misclassification rate were computed.
    - ROC curves and AUC values were analyzed to understand the trade-offs between true positive rate and false positive rate at different thresholds.

2. **Confusion Matrix and Error Metrics**:
    - Confusion matrices were generated for each model to detail the counts of true positives, false positives, true negatives, and false negatives.
    - Derived error metrics provided a comprehensive performance comparison among the models.

3. **Support Vector Machine (SVM)**:
    - Implemented SVM with RBF kernel to handle non-linear decision boundaries.
    - Explored the impact of Gaussian parameter (σ) and cost function (C) on model performance.
    - Evaluated SVM using the same error metrics and ROC-AUC analysis.

4. **Advantages and Disadvantages**:
    - Discussed the benefits and limitations of using SVMs in high-dimensional and complex datasets.

The project's R code, including data preprocessing, model training, evaluation, and visualization, is available in the repository.
