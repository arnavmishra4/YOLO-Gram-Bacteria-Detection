# YOLO-Gram-Bacteria-Detection


## Files and Structure

- **ParameterOptimization.ipynb**: This notebook focuses on hyperparameter optimization using the Optuna library. We employ Optuna to find the optimal set of hyperparameters for the model. At the end of this notebook, we print the best parameters identified during the optimization process.

- **Best_Model.ipynb**: In this notebook, we use the optimal hyperparameters obtained from `parameteroptimization.ipynb` to train the model. This ensures the model achieves the best possible performance based on the hyperparameter tuning conducted.

## Usage

1. Run `ParameterOptimization.ipynb` to perform hyperparameter tuning with Optuna. The best parameters are printed at the end of the notebook.
2. Take these optimized parameters and use them in `Best_Model.ipynb` to train the model.
