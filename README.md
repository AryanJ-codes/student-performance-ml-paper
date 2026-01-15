# Student Performance Prediction using Classical Machine Learning

This repository accompanies the research paper:

**“Simpler is Better: Empirical Evaluation of Classical Machine Learning Models for Predicting Student Performance in Online Education”**

The study evaluates and compares classical machine learning models on the Open University Learning Analytics Dataset (OULAD).

## 📄 Paper
- [Read the full paper (PDF)](paper/student_performance_ml.pdf)

## 🧠 Models Evaluated
- Logistic Regression (L1, L2)
- Support Vector Machine (L1, L2)
- Random Forest
- Gradient Boosting
- XGBoost

## 📊 Experimental Setup
- Dataset: Open University Learning Analytics Dataset (OULAD)
- Task: Binary classification (Pass / Fail)
- Train-validation-test splits:
  - 80 / 10 / 10
  - 70 / 15 / 15
  - 60 / 20 / 20
- Metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC

## 📈 Results

### ROC-AUC Curves

**80/10/10 Split**  
![ROC 80](results/figures/roc_curve_80_10_10.png)

**70/15/15 Split**  
![ROC 70](results/figures/roc_curve_70_15_15.png)

**60/20/20 Split**  
![ROC 60](results/figures/roc_curve_60_20_20.png)

### Model Performance Comparison

**80/10/10 Split**  
![Metrics 80](results/figures/metrics_comparison_80.png)

**70/15/15 Split**  
![Metrics 70](results/figures/metrics_comparison_70.png)

**60/20/20 Split**  
![Metrics 60](results/figures/metrics_comparison_60.png)

## 📂 Repository Structure
student-performance-ml/
│── README.md
├── paper/
│ └── student_performance_ml.pdf
└── results/
└── figures/

## 👤 Authors
- Aryan Jhamnani  
- Arham Jain  
