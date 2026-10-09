# Credit Card Fraud Detection

## Project Overview
This project uses Machine Learning to identify potentially fraudulent credit card transactions. It uses Logistic Regression to classify transactions as genuine or fraudulent.

## Objective
To build a classification model that detects fraudulent transactions and evaluate its performance using appropriate metrics.

## Dataset
The project uses the Credit Card Fraud Detection dataset from Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains transaction features, including Time, Amount, V1-V28, and a Class column.

- Class 0: Genuine transaction
- Class 1: Fraudulent transaction

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Load and explore the dataset.
2. Check missing values and duplicate records.
3. Separate features and target.
4. Split data into training and testing sets.
5. Scale the Time and Amount features.
6. Train a Logistic Regression model.
7. Evaluate the model using classification metrics and visualizations.

## Model Performance
Results from the current test set:

- Accuracy: 99.92%
- Precision: 82.89%
- Recall: 64.29%
- F1-score: 72.41%
- ROC-AUC: 0.9559

These results are from one train-test split. Accuracy alone is not sufficient for evaluating fraud detection because fraudulent transactions are rare.

## How to Run
1. Download the dataset from the Kaggle link above.
2. Place `creditcard.csv` in the project folder.
3. Install the required Python libraries.
4. Open `credit_card_fraud_detection.ipynb` in Jupyter Notebook.
5. Run the notebook cells in order.

## Project Files
- `credit_card_fraud_detection.ipynb`: Data exploration, model training, and evaluation.
- `fraud_detection_model.pkl`: Saved Logistic Regression model.
- `fraud_detection_scaler.pkl`: Saved feature scaler.

## Disclaimer
This is an educational machine learning project and is not intended for real-world financial decisions.
