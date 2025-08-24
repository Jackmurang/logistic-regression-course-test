# 🧠 Logistic Regression Models – Supervised Learning Course 1
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jackmurang/logistic-regression-course-test/main?filepath=coded_regularized_logistic_regression_QAmanager_model.ipynb)
> 🚀 Launch the notebook instantly in Binder (no install required!)

This repository contains hands-on implementations of logistic regression models developed during my ML coursework. It includes both regularized and unregularized versions, utility scripts, and test cases for reproducibility and evaluation.

## 📁 Project Structure

- `coded_regularized_logistic_regression_QAmanager_model.ipynb`  
  → Regularized logistic regression for QA manager classification  
- `coded_unregularized_logistic_regression_admin_model.ipynb`  
  → Baseline logistic regression for admin classification  
- `Microchip_QA_manager_scikit_learn.ipynb`  
  → Scikit-learn implementation for comparison  
- `utils.py`  
  → Helper functions for data processing and evaluation  
- `test_utils.py`, `public_tests.py`  
  → Unit tests to validate core logic

## ⚙️ Setup

To recreate the environment used in this project:

```bash
conda env create -f environment.yml
conda activate logreg_env
