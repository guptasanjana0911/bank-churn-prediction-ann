# Bank Customer Churn Prediction using ANN

## Objective
Identify bank customers at high risk of churning so the bank can plan retention strategies.

## Tools
Python, TensorFlow/Keras, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn

## Methods
- Preprocessing: label encoding and standard scaling
- Model: feedforward ANN with ReLU hidden layers and sigmoid output
- Training: binary cross-entropy loss, Adam optimizer
- Evaluation: confusion matrix, ROC-AUC, learning curves

## Results
- ROC-AUC: 0.86
- Learning curves show stable convergence with minimal gap between training and validation accuracy

## Files
- `churn_ann.ipynb`: code
- `report.pdf`: full project report
