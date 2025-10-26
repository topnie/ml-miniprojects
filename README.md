# Traditional ML Miniprojects

Two Jupyter notebooks that demonstrate classic (non-deep) machine learning workflows: data exploration, feature engineering / selection, model building, nested cross-validation, and validation on unseen data.

Notebooks
- `task1.ipynb` — data description, clustering and classification (AdaBoost), regression with feature selection using statsmodels and cross-validation.
- `task2.ipynb` — baseline and advanced pipelines for regression and classification (LinearRegression, RidgeCV, SVC, RandomForest), nested CV and permutation / importance-based feature selection.

Notes
- The notebooks include fixed random_state seeds for reproducibility.
- Hyperparameter choices and feature counts are documented in the notebooks; they were tuned for demonstration, not production.
- Datasets are intentionally not included.
- To run the notebooks, add the required CSV files to the notebook directory with the expected names:
  - `task2_data.csv`
  - `validation_data.csv`
  - `earnings.csv`
- If you add your own datasets, ensure column names match those referenced in the notebooks (see top of each notebook for expected column names).
