# Machine Learning Notebook Collection

A practical collection of Jupyter notebooks covering supervised learning, preprocessing, model comparison, and evaluation across several tabular and text datasets.

## Included projects

| Notebook | Focus |
| --- | --- |
| `Cancer.ipynb` | Classification and class balancing |
| `Churn.ipynb` | Customer churn classification |
| `Compressive Strength.ipynb` | Regression and ensemble models |
| `Credit_Risk.ipynb` | Credit-risk classification |
| `Diabetes.ipynb` | Classification and model voting |
| `EU-Soccer.ipynb` | Sports-data regression |
| `Fuel_Consumption.ipynb` | Fuel-consumption regression |
| `HouseJadi.ipynb` | House-price regression |
| `Spam.ipynb` | NLP and spam classification |
| `Student.ipynb` | Student-performance modeling |

## Environment

```bash
python -m venv .venv
pip install jupyter pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost nltk joblib
jupyter notebook
```

Datasets may need to be downloaded separately or paths updated inside individual notebooks.

## Scope

These notebooks are educational experiments. Metrics depend on each dataset and split; results should not be treated as production benchmarks or used for high-impact decisions without independent validation.
