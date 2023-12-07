# Prediction of horses health using Catboost (+Optuna tuning)


Main goal of this project: Develop a robust model for predicting horse health outcomes based on horse health indicators and other data. The dataset used is synthetic and generated from the Horse Survival Dataset, which can be found at www.kaggle.com/datasets/yasserh/horse-survival-dataset.

The project involves two datasets: training data with 1235 entries and testing data with 824 entries (refer to the /data folder).

Key steps in the project include:

- Exploratory Data Analysis (EDA)
- Feature engineering
- One-Hot Encoding (OHE) and other categorization techniques
- Checking absolute correlations
- Optuna model tuning
- Model training using CatBoost
- Generating final predictions
- Validation

The model was validated on the test data, yielding the best result of 0.75303. A more detailed explanation is provided in the accompanying .ipynb file.

Technical stack used in the project: Python, pandas, matplotlib, scikit-learn, CatBoost, Optuna.