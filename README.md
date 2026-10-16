# Credit Card Fraud Detection - CODTECH Task 4

## Objective
Detect fraudulent credit card transactions using machine learning.

## Dataset
- File: creditcard.csv (Kaggle)
- 284,807 transactions, 492 frauds (highly imbalanced)
- Features: V1-V28 (PCA transformed), Amount, Time
- Target: Class (0=Normal, 1=Fraud)

## Model
RandomForestClassifier (50 trees)
Used 20k sample for faster training on local machine.

## Result
Accuracy: ~99.5%
Precision, Recall reported in classification report.

## How to Run
pip install pandas scikit-learn
python fraud_detection.py

## CODTECH Internship
