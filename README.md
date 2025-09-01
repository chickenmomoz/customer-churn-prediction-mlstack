Churn Prediction

This repository contains a machine learning workflow for customer churn prediction.
The project uses Python (pandas, scikit-learn, matplotlib, seaborn) for EDA, feature engineering, model training, validation, and prediction.

Project Structure
CHURN-PREDICTION/
│── notebooks/
│    └── churn.ipynb        # Main notebook with full pipeline
│
│── requirements.txt        # Dependencies
│── README.md               # Project overview
│── .gitignore              # Ignore unnecessary files
│── LICENSE                 # MIT License
│── src/                    # Placeholder for future scripts

Features

Data Preprocessing: Cleans and encodes customer data.

Model Training: Machine learning models trained using cross-validation.

Validation:

ROC-AUC score is computed on validation folds.

Classification reports can be generated.

Test Evaluation:

Predictions on the test set are compared against a baseline (majority class).

Average predicted churn risk is compared with the training churn rate.

Sanity checks ensure predictions are consistent with data distribution.
