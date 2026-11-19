# Bioinformatics Project: Faizah Khan - 1002058205
Breast Cancer Bioinformatics Project - Fall 2026
# Identifying Key Cellular Features of Breast Tumor Malignancy using Machine Learning

** In draft stage as of 11/19/26**

## Research question
Can machine learning models identify which cellular features are most informative for distinguishing benign from malignant breast tumors?

## Dataset
Wisconsin Diagnostic Breast Cancer (WDBC): 569 samples, 30 numeric features computed from digitized fine needle aspirate images (357 benign, 212 malignant).
Source: UCI Machine Learning Repository / Kaggle (https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data). File: `data.csv`.

## Repository contents
- `BreastCancerNotebook.ipynb` – analysis notebook (preprocessing, EDA, correlation analysis and feature reduction, baseline Random Forest)
- `data.csv` – dataset
- `ai_usage.md` – documentation of AI tool use
- `README.md` – this file

## How to run
1. Open the notebook in Google Colab.
2. Upload `data.csv` to the Colab session (update the file path in the first cell if needed).
3. Run all cells from top to bottom.
Libraries: pandas, NumPy, matplotlib, seaborn, scikit-learn. [Python/library versions]
Random seeds: train/test split random_state = 42; Random Forest random_state = 43.

## Project status (draft)
- Week 1 complete: data inspection, cleaning, EDA, correlation analysis, feature reduction (30 → 16 features)
- Week 2 in progress (about one day behind): train/test split and baseline Random Forest done (96.5% test accuracy); Logistic Regression, SVM, KNN, cross-validation, and PCA still to do
- Week 3 planned: final visualizations, interpretation, final report

## Credits
Parts of the exploratory data analysis and baseline Random Forest code were adapted from a public Kaggle notebook: [DATA1 on Kaggle].
