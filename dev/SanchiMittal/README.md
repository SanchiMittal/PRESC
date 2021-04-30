# ML Model Evaluation on Wine Quality prediction 
Dataset used : [winequality.csv](https://github.com/SanchiMittal/PRESC/blob/models_winequality/datasets/winequality.csv) (source : https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

This project was done as a task for resolving one of the issues in the [PRESC](https://github.com/mozilla/PRESC) repository while I was participating in [Outreachy](https://www.outreachy.org/) applications, Summer 2020.

My work that __got merged__ into the repository : https://github.com/mozilla/PRESC/tree/archisha-chandel/covariate/dev/SanchiMittal

This folder here now contains further evaluation and digging using data analysis.

### Contents

- models_on_winequality.ipynb - This notebook applies and evaluates the performance of various machine learning models (logistic regression, KNN, Random Forest Classifier, SVM, Naive Bayes, etc.) on the Wine Quality Dataset.

- Undersampled_winequality.ipynb - The data being non-uniform with regards to the class distribution, produced better results with undersampling, as has been showed in the notebook (using Random Forest Classifier).

- dataloader.py - Module with functions for importing dataset and pre-processing it.

- models_eval.py - This module has functions to train and test the ML model, followed by its performance evaluation.
