# Support Vector Machines (SVM) Classification

## Objective
Implement Support Vector Machines (SVM) for both linear and non-linear classification using the Breast Cancer dataset.  
Demonstrates margin maximization, kernel trick, hyperparameter tuning, and decision boundary visualization.


## Tools & Libraries
- Python
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
**Dataset:** Breast Cancer dataset (from `sklearn.datasets`)


## Steps Implemented
1. Load and prepare dataset for binary classification.
2. Train SVM with **Linear** and **RBF** kernels.
3. Visualize decision boundaries for both kernels.
4. Tune hyperparameters `C` and `gamma`.
5. Evaluate performance using classification reports.
6. Apply cross-validation to check generalization.


## Results

Linear Kernel: Good for linearly separable data.

RBF Kernel: Handles complex non-linear decision boundaries.

Cross-validation confirms strong generalization.
