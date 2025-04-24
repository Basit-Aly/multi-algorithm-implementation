# Multialgorithm Evaluation on UCI Classification Datasets

This project evaluates the performance of multiple machine learning algorithms using five classification datasets from the UCI Machine Learning Repository. The goal was to analyze and compare models using 10x10-fold cross-validation across key performance metrics.

##  Datasets Used

1. **Breast Cancer Wisconsin (Diagnostic)**
2. **Mushroom Dataset**
3. **Statlog (German Credit Data)**
4. **Student Performance Dataset**
5. **Spambase**

Each dataset was selected based on diversity in structure, application domain, and class distribution, ensuring a robust comparison of models.

## Methodology

- **Preprocessing:** Data cleaning, encoding, normalization
- **Modeling:** Implementation of 9 classification algorithms
- **Evaluation:** 10x10 Fold Cross-Validation
- **Metrics:**
  - **Average Accuracy**
  - **Average F-Measure**
  - **Average AUC**

## Algorithms Implemented

1. Decision Tree (C4.5)
2. Decision Tree (CART)
3. Support Vector Machine (Linear Kernel)
4. Support Vector Machine (RBF Kernel)
5. Naïve Bayes
6. Logistic Regression
7. 3 Layer Fully Connected Neural Network
8. 3 Layer Fully Connected Neural Network with L2 Regularization
9. 3 Layer Fully Connected Neural Network with L1 Regularization

## Results

Each model was evaluated using the same cross-validation strategy to ensure comparability. Summary tables and visualizations are provided in the notebook for deeper insights into algorithm performance across different datasets.


## Files

- `main.ipynb` : Colab Notebook containing all the code and analysis.


