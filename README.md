# Project Overview
This project focuses on predicting maximum height of cloud using various machine learning techniques. It includes data preprocessing, model development, and hyperparameter tuning. The primary goal is to accurately predict maximum height of cloud values in a meteorological context using classification and regression approaches.

## Repository Structure

### Notebooks

1. **Hmax Prediction Classification**
   - **Total Cells**: 72 (Markdown: 15, Code: 57)
   - **Main Topics**: Data preprocessing, model selection, L1 Regularization, SVM, Random Forest, CatBoost, XGBRegressor, LightGBM, Stacking.
   - **Libraries Used**: NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn, XGBoost, LightGBM, CatBoost, Optuna, Scipy, Random, Warnings.

2. **Hmax Prediction Regression**
   - **Total Cells**: 59 (Markdown: 12, Code: 47)
   - **Main Topics**: Similar to the classification notebook but focuses on regression approaches.
   - **Libraries Used**: Similar to the classification notebook.

3. **Preprocessing (Preproc)**
   - **Total Cells**: 6 (Markdown: 1, Code: 5)
   - **Main Topics**: Useful functions and preprocessing steps.
   - **Libraries Used**: NumPy, Pandas, Matplotlib, Seaborn.

### Data Files
1. **Расчёт регрессии_220322.xlsx**
   - Excel file containing data used for regression analysis.

2. **Выборка случаев для прогноза ОЯ.xlsx**
   - Excel file containing a selection of cases for 'Hmax' prediction.

## How to Use
- Each notebook is self-contained with comments and markdown cells explaining the steps.
- Data preprocessing must be done using 'Preproc.ipynb' before applying models.
- Models can be tested and tuned as per the methods shown in the classification and regression notebooks.

## Requirements
- Python 3.x
- Relevant Python libraries as listed in each notebook.
