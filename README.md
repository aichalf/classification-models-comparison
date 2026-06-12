# 📊 Classification Algorithms Comparison — ML Benchmarking

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> Systematic benchmarking of 3 classification algorithms — Logistic Regression, Decision Tree, and KNN — with full evaluation metrics and comparative analysis.

## 📌 Overview

This project evaluates how different classification models behave on the same structured dataset, providing a side-by-side comparison to support informed model selection in real-world scenarios.

## 🎯 Models Compared

| Model | Strengths | Best When |
|---|---|---|
| Logistic Regression | Interpretable, fast | Linear boundaries, probability output needed |
| Decision Tree | Visual, non-linear | Non-linear patterns, explainability needed |
| K-Nearest Neighbors | Simple, no training | Small datasets, local patterns |

## 📐 Evaluation Metrics
- **Accuracy** — overall correctness
- **F1-Score** — balance between precision and recall
- **Precision** — reliability of positive predictions
- **Recall** — coverage of actual positives
- **Confusion Matrix** — per-class breakdown

## 🔍 ML Pipeline
1. Data loading and preprocessing
2. Train/test split with stratification
3. Model training (default + tuned hyperparameters)
4. Cross-validation (k-fold)
5. Metric comparison and visualization

## 🛠️ Tech Stack
`Python` · `scikit-learn` · `pandas` · `NumPy` · `Matplotlib` · `Seaborn`

## 💼 Business Applications
- Model selection framework for data science teams
- Baseline benchmarking before deploying advanced models
- Educational reference for ML practitioners

## 🚀 Run Locally
```bash
git clone https://github.com/aichalf/classification-models-comparison
pip install scikit-learn pandas numpy matplotlib seaborn
# Open notebooks in Jupyter or Google Colab
```

## 👩‍💻 Author
**Aicha Lfakir** · [LinkedIn](https://linkedin.com/in/aicha-lfakir) · [GitHub](https://github.com/aichalf)
