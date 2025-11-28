# Machine Learning Models 

This repository contains a simple machine learning workflow for predicting target properties from a structured dataset. The workflow is implemented in four Jupyter notebooks, each corresponding to a different regression algorithm, all using the same dataset stored in `dataset.xlsx`.

You can adapt this repository to your own regression task by modifying the dataset and the feature/target column selections inside the notebooks.

---

## Repository Structure

- `dataset.xlsx`  
  Main dataset used for training and evaluating all models.  
  Each row corresponds to one sample, and columns contain input features and at least one target property.

- `gkrr_method.ipynb`  
  Gaussian Kernel Ridge Regression (GKRR) model:
  - Data loading and preprocessing  
  - Train/validation/test splitting  
  - Model training and evaluation  

- `knn_method.ipynb`  
  k-Nearest Neighbors (KNN) regression model:
  - Data loading and preprocessing  
  - Train/validation/test splitting  
  - Model training and evaluation  

- `rf_method.ipynb`  
  Random Forest (RF) regression model:
  - Data loading and preprocessing  
  - Train/validation/test splitting  
  - Feature importance analysis 
  - Model training and evaluation  

- `xgboost_method.ipynb`  
  XGBoost regression model:
  - Data loading and preprocessing  
  - Train/validation/test splitting  
  - Model training and evaluation  

---

## Requirements

The notebooks assume a Python environment with the following packages:

- Python ≥ 3.8  
- `numpy`  
- `pandas`  
- `scikit-learn`  
- `matplotlib`  
- `xgboost`  
- `jupyter` or `jupyterlab`

You can install the dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib xgboost jupyter
