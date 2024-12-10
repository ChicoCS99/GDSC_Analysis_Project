# GDSC Analysis Project

This project explores the **Genomics of Drug Sensitivity in Cancer (GDSC)** dataset to predict drug sensitivity in cancer cell lines using machine learning. The analysis is performed in **Google Colab** and aims to classify cell lines as *sensitive* or *resistant* to drugs.

## Project Overview
- **Dataset**: [GDSC from Kaggle](https://www.kaggle.com/datasets/samiraalipour/genomics-of-drug-sensitivity-in-cancer-gdsc).
- **Tools Used**: 
  - Google Colab for coding and analysis.
  - Python libraries: Pandas, Scikit-learn, Matplotlib, Seaborn, XGBoost, Imbalanced-learn.
- **Key Techniques**:
  - Data preprocessing and feature encoding.
  - Balancing the dataset with SMOTETomek.
  - Training and tuning models (Random Forest and XGBoost).
  - Evaluation with precision, recall, F1-score, and AUC-ROC metrics.

## How to Reproduce
1. Open the `.ipynb` file in Google Colab.
2. Run the notebook step-by-step to reproduce the analysis.
3. Ensure the dataset (if required) is downloaded and placed in the correct path.

## Results
The analysis highlights the importance of features such as drug IDs, target pathways, and tissue descriptors in predicting drug sensitivity. The XGBoost model, after hyperparameter tuning, demonstrates robust performance with enhanced accuracy and recall.

## Files in this Repository
- **GDSC_Analysis_Project.ipynb**: The Jupyter Notebook containing the full project code.
- **README.md**: This documentation.
- **archive.zip**: Dataset used in this project .

---



