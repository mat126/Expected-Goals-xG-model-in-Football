# xG Model Selection in Football

This repository presents a comparative evaluation of statistical and machine learning models for estimating Expected Goals (xG) in football, using a cleaned and enriched open-source dataset.

📘 **Notebook**: [`notebooks/xg-model-selection.ipynb`](notebooks/xg-model-selection.ipynb)  
📊 **Dataset**: [Kaggle - Shots Dataset for Football](https://www.kaggle.com/datasets/mat126/shots-dataset-for-footballsoccer)  
📄 **Published Article**: [Zenodo DOI](https://doi.org/10.5281/zenodo.16034196)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16034196.svg)](https://doi.org/10.5281/zenodo.16034196)

---

## Models Compared

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Bagging Classifier
- Random Forest (with GridSearchCV tuning)
- Feedforward Neural Network (Keras + TensorFlow)
- SHAP Explainability for neural models

## Evaluation Metrics

- Confusion Matrix (threshold = 0.3)
- ROC Curve & AUC
- Calibration Curve
- Precision, Recall, F1-score
- Brier Score

## Installation

To reproduce the environment:

```bash
pip install -r requirements.txt
```

---

## License

This project is distributed under the MIT License.
