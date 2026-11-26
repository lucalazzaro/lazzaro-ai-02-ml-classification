# AutomaParts — Defective Part Classification (Machine Learning)

> Project developed as part of the Master in AI Solution Architecture
> (ProfessionAI) — Machine Learning module. Educational case study.

## Description
A supervised classification project for AutomaParts S.p.A., a fictional
automotive tier-1 supplier. The goal is to predict whether a precision
mechanical part is defective at the end of the in-line inspection process,
using dimensional measurements, process parameters and line information.

## Stack
- Python 3
- pandas, NumPy
- scikit-learn (Decision Tree, Random Forest, Logistic Regression)
- scipy.stats, seaborn, matplotlib
- Jupyter / Google Colab notebook

## Demonstrated skills
- Exploratory data analysis (EDA) and class-imbalance assessment
- Missing-value analysis and treatment criteria
- Outlier handling and feature preparation (encoding, scaling)
- Point-biserial correlation with a binary target
- Train/test split and generalisation evaluation
- Comparison of supervised models and their trade-offs in an industrial context

## How to run
Open `AutomaParts.ipynb` in Google Colab or Jupyter, then run the cells in order.

```bash
pip install pandas numpy scikit-learn scipy seaborn matplotlib jupyter
jupyter notebook AutomaParts.ipynb
```

The first code cell loads the dataset from a public GitHub URL, so an internet
connection is required. No API keys are needed.

## Note
- Educational case study. All data, companies and contacts mentioned in the
  code are entirely fictional.
- The dataset is not stored in this repository; it is loaded at runtime.
