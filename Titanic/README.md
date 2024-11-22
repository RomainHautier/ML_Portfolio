# Titanic Survival Prediction

This project predicts passenger survival on the Titanic using machine learning techniques. It includes:

- Feature engineering
- Model building
- Model Training & Evaluation
- Predictions on an unseen test set later submitted to Kaggle.com

## Files
- `FeatEngFun.py`: Feature engineering functions
- `GridSearch.py`: Model optimization script
- `featengtest.ipynb`: Jupyter notebook for feature testing and exploration
- enable_grid_search: File containing the names of the models to be used in the GridSearch operation performed when running the main function with the 'train.csv' dataset.
- scaler.pkl: saved StandardScaler() instance to standardize the 'Fare' and 'Age' columns of the dataset according to the scaling process fit on the training set (train.csv).
- updated_models & updated_models.pkl: best instances of each model obtained during the GridSearch Operation.

## Requirements
- Python 3.8+
- Libraries: pandas, numpy, sklearn, pickle, seaborn, matplotlib
