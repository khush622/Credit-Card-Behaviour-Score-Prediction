# Credit-Card-Behaviour-Score-Prediction

# Credit Card Behaviour Score Prediction

A machine learning pipeline to predict customer credit behavior scores using demographic and transactional features. This project helps financial institutions identify potential delinquents and improve credit risk management.

---

## 🔍 Project Highlights

- **Custom Dataset**: Realistic, non-Kaggle dataset with behavioral and demographic features.
- **Feature Engineering**: Includes credit utilization, delinquency streaks, payment patterns, etc.
- **Models Used**: Logistic Regression, Random Forest, XGBoost, and Neural Networks.
- **Evaluation**: Optimized for F2-score, Recall, and AUC to prioritize risk detection.
- **Ensemble**: Combines SVM, XGBoost (with threshold tuning), and a Neural Network (best F2 checkpoint) via soft voting.

---

## 🧪 Workflow

1. **Preprocessing**
   - Missing value handling
   - Feature encoding, scaling, and streak feature generation

2. **Modeling**
   - Individual model training and validation
   - Threshold tuning for imbalanced classification

3. **Ensembling**
   - Soft voting across selected models
