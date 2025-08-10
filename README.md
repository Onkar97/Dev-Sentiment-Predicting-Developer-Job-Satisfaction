# DevSentiment – Predicting Developer Job Satisfaction

This project analyzes developer survey data to predict job satisfaction using classical ML models. It includes preprocessing (missing value handling, encoding, normalization), model training (Logistic Regression, Random Forest, SVM), and feature importance analysis.

## Features
- **EDA & Cleaning:** handle missing values, encode categoricals, normalize features
- **Modeling:** Logistic Regression, Random Forest, SVM with hyperparameter tuning
- **Evaluation:** accuracy, F1, ROC-AUC; feature importance and driver analysis
- **Reproducible Notebooks:** 1 Jupyter notebook(s)

## Tech Stack
- **Language:** Python 3.9+
- **Libraries:** pandas, scikit-learn, numpy, matplotlib (typical)
- **Environment:** Jupyter Notebook

## Getting Started
```bash
python -m venv .venv
.\.venv\Scriptsctivate  # Windows
pip install -r requirements.txt  # if provided
# otherwise install libs manually
jupyter lab  # or jupyter notebook
```
Open the notebook(s) and run cells top-to-bottom.

## Repository Structure
```
data/                # raw/processed datasets (if provided)
notebooks/           # Jupyter notebooks (.ipynb)
src/                 # utility python files (if any)
requirements.txt     # optional
README.md
```

## Results (example)
- Accuracy: **~87%**
- Key drivers: **compensation**, **flexibility**, **tech stack preferences**
