 Overview

This project focuses on predicting customer responses for a bank marketing campaign using binary classification. The goal is to determine whether a customer will subscribe to a product or not based on historical data.
ools & Libraries

Python 3.x
Pandas, Numpy
Scikit-learn (train-test split, metrics)
CatBoost (Classifier)
Optuna (Hyperparameter optimization

Approach

Data preprocessing and handling categorical features.

Splitting the data into training and validation sets.

Hyperparameter tuning using Optuna to optimize CatBoost performance.

Training the final model on the full dataset.

Evaluating the model using Accuracy, F1-score, Precision, Recall, and Confusion Matrix.

Results

Validation Accuracy: 93%

F1-score: 0.83

 Key Learnings

Handling categorical features efficiently with CatBoost.

Using Optuna for automatic hyperparameter tuning.

Transforming real-world banking data into actionable predictions.
Clone this repository:

git clone https://github.com/Areenalmahameed/Binary-Classification-with-a-Bank-Dataset.git


Install required libraries:

pip install pandas numpy scikit-learn catboost optuna


Run the notebook bank.ipynb to reproduce results.
