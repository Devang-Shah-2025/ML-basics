# ML Basics — Learning Playground

This repository is a personal learning playground for getting started with machine learning. It contains notebooks, raw datasets, and notes used while learning core ML concepts and workflows.

## Project Overview

- This workspace is for practicing core machine learning tasks: data loading, exploratory data analysis (EDA), preprocessing, modeling, evaluation, and model selection.
- Notebooks demonstrate step-by-step examples and experiments you can run and extend.

## Datasets

- `magic04.data` — a dataset included in this workspace used for practicing classification tasks (raw data file).
- `GAMMA.ipynb` — an example Jupyter notebook in the root demonstrating workflows and experiments.

Place additional datasets in the project root or a `data/` folder and update notebooks accordingly.

## Learning Goals

- Understand the ML workflow: problem definition → data collection → preprocessing → modeling → evaluation → deployment (conceptual).
- Practice common preprocessing steps: missing values, encoding categorical variables, scaling, feature selection.
- Train and evaluate baseline models: Logistic Regression, k-NN, Decision Trees, Random Forests, SVM, Naive Bayes.
- Learn evaluation metrics: accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices.
- Use train/test split and cross-validation for robust evaluation.
- Basic hyperparameter tuning (grid search) and simple pipelines.

## Notebooks & Code

- `GAMMA.ipynb` — primary notebook to run experiments and follow along with examples.

Suggested structure for new notebooks:

1. Problem statement and objective
2. Data loading and initial inspection
3. Exploratory Data Analysis (visualizations, distributions, correlations)
4. Preprocessing and feature engineering
5. Model training (baseline → improvements)
6. Evaluation and interpretation
7. Next steps and experiments

## Setup & Run (local)

1. Create a virtual environment (recommended):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install minimal dependencies:

```powershell
pip install -U pip
pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab notebook
```

3. Start JupyterLab or run the notebook:

```powershell
jupyter lab
# or
jupyter notebook GAMMA.ipynb
```

## Tips & Best Practices

- Start with a small subset of data to iterate quickly. Then scale up.
- Always visualize features and class balance before modeling.
- Use pipelines (`sklearn.pipeline.Pipeline`) to bundle preprocessing and modeling.
- Use stratified splits for classification to preserve class distribution.
- Track experiments (parameters, metrics) with a simple CSV or lightweight tool.

## Next Steps / Experiments

- Try feature engineering: interaction terms, polynomial features, and domain-specific features.
- Compare model performance with cross-validation and nested cross-validation for hyperparameter tuning.
- Learn and apply model interpretability techniques (SHAP, permutation importance).
- Experiment with ensembles (bagging, boosting) and simple neural networks.

## Resources

- scikit-learn documentation: https://scikit-learn.org
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (book) — a good practical guide.
- Coursera / fast.ai / free online courses for structured learning paths.

## License

This is a personal learning repository. Use the contents for study purposes.

---

Happy learning — add more notebooks and datasets as you go! 🎓
