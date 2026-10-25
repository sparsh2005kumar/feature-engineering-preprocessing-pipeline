# Feature Engineering & Preprocessing Pipeline

This project demonstrates a leak-free Scikit-Learn preprocessing pipeline with:
- train/test split before transformations,
- numeric imputation and scaling,
- categorical imputation and one-hot encoding,
- `ColumnTransformer` + `Pipeline`,
- baseline comparison and permutation feature importance.

## Run
Install dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```
Open `feature-engineering-preprocessing-pipeline.ipynb` in Jupyter Notebook or VS Code.

## Dataset note
The notebook generates a reproducible synthetic mixed-type dataset so the workflow runs without downloading third-party data. The dataset is not real-world data; metrics and feature importance are demonstration-only. For a production-quality portfolio submission, replace the synthetic data-generation section with a documented, permitted real dataset and record its source/license.
