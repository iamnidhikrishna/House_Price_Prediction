# California House Price Prediction using XGBoost

## Project Description
This regression project predicts median house prices in California based on features such as income, location, population, and housing characteristics. The goal is to demonstrate how gradient boosting models like XGBoost can be used for accurate price prediction in real estate analytics.

## Model Used
XGBoost Regressor

## Dataset
California Housing Dataset (available via `sklearn.datasets`)

## Performance
- R² Score (Train): 0.94
- R² Score (Test): 0.83
- Mean Absolute Error (Test): 0.31

## Files
- `house-price-predictor.ipynb` – Full workflow including data loading, preprocessing, model training, evaluation, and visualization.
- No external dataset file required (loaded directly from `sklearn.datasets`)

## How to Run
1. Clone the repository:
```

git clone [https://github.com/](https://github.com/)<your-username>/house-price-xgboost.git
cd house-price-xgboost

```

2. Install dependencies:
```

pip install -r requirements.txt

```

3. Open the notebook:
```

jupyter notebook house-price-predictor.ipynb

```
Or run in Google Colab

## Requirements
See `requirements.txt` for the list of dependencies.
