### regression-surrogates

[![DOI](https://zenodo.org/badge/310509538.svg)](https://zenodo.org/badge/latestdoi/310509538)

This repo contains the code for running machine learning (ML)-based surrogate models in the paper 
" Surrogate models based onmachine learning methods for parameter estimation of leftventricular myocardium "

we use  three  ML-based  surrogate  models,  namely  K-nearest  neighbour(KNN) , XGBoost and multi-layer perceptron . The three chosen ML models can be considered to be a supervised learning regression problem.  After training process,  we further  apply  the  three  ML-based  surrogate  models  for parameter estimation.

### Requirements

The code requires Matlab2016, Python (3.6+) and the following dependencies: [scikit-learn](https://scikit-learn.org/stable/), [pandas](https://pandas.pydata.org/pandas-docs/stable/), [numpy](https://numpy.org/doc/), [Scipy](https://docs.scipy.org/doc/), [xgboost ](https://xgboost.readthedocs.io/en/latest/),[joblib](https://joblib.readthedocs.io/en/latest/).

To setup, either run,  you can download this repo and better prepare a pip environment:

```
cd .
pip install --upgrade pip
pip install -r requirements.txt
```

