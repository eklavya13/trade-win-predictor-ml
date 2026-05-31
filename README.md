# AI Trading Journal - Trade Outcome Predictor

## Overview

This machine learning project predicts whether a trade is likely to result in a win or loss based on historical trading journal data.

The objective is to help traders identify patterns in their decision-making process and improve trading performance through data-driven insights.

## Dataset

The model was trained using a custom trading journal dataset containing historical trade information and outcomes.

## Machine Learning Pipeline

- Data Cleaning
- Feature Engineering
- One-Hot Encoding
- Train-Test Split
- Random Forest Classification
- Model Evaluation

## Model Performance

| Metric | Score |
|----------|----------|
| Accuracy | 86.36% |
| Precision | 86% |
| Recall | 92% |
| F1 Score | 89% |

## Confusion Matrix

See `Screenshots/confusion_matrix.png`

## Files

- `Notebooks/AI_Trading_Journal.ipynb` - Complete training notebook
- `Models/random_forest_model.pkl` - Trained model
- `Models/model_columns.pkl` - Feature schema
- `Data/Trades2.csv` - Dataset

## Future Improvements

- FastAPI API Deployment
- Real-Time Trade Predictions
- Interactive Web Dashboard
- Advanced Feature Engineering

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook
