# Ames-house-prices

Here we practice some regression techniques using a tabular dataset on house prices in Ames, Iowa.

Some key steps that were taken to produce the final predictions:
* Un-ordered categorical features were target encoded, rather than the more typically employed one hot encoding.
* Hyperparameter tuning was performed using a Bayesian hyperparameter optimization method.
* Three variants of gradient boosted trees are used: a vanilla gradient boosting regressor, light gradient boosting (light GBM), and extreme gradient boosting (XGB).
* A stacked meta-learner was also used.
* The final prediction is produced via the weighted average of predictions made using the 4 models listed above.

This notebook was executed on a Kaggle kernel, within the context of [this ongoing Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). If you'd like to fork this notebook with the associated data, please visit the version of this notebook that is hosted on Kaggle, available [here](https://www.kaggle.com/yuempark/ames-iowa-house-price-prediction).
