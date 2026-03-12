# Credit Card Fraud Detection (Machine Learning)

## Project Overview
This project builds machine learning models to detect fraudulent credit card transactions. Fraud detection is a critical problem for financial institutions because fraudulent transactions are rare compared to normal ones.

The dataset is highly **imbalanced**, making this a challenging classification problem.

---

## Dataset

Source: Kaggle – Credit Card Fraud Detection Dataset

Dataset characteristics:

- 284,807 transactions
- 492 fraud cases
- Highly imbalanced dataset
- Features V1–V28 are PCA-transformed for privacy
- Target variable: **Class**
  - 0 → Normal transaction
  - 1 → Fraudulent transaction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Models

### Logistic Regression

Results:

- Fraud Precision: **0.83**
- Fraud Recall: **0.64**
- F1 Score: **0.72**

---

### Random Forest Classifier

Results:

- Fraud Precision: **0.94**
- Fraud Recall: **0.82**
- F1 Score: **0.87**

Random Forest significantly improved fraud detection performance compared to Logistic Regression.

---

## Model Evaluation

We evaluated the model using:

- Classification Report
- Confusion Matrix
- Precision
- Recall
- F1 Score

Random Forest detected significantly more fraudulent transactions.

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Handling Imbalanced Data
4. Feature Scaling
5. Train/Test Split
6. Logistic Regression Model
7. Random Forest Model
8. Model Evaluation
9. Confusion Matrix Visualization

---

## Future Improvements

Possible improvements to enhance the model:

- SMOTE (Synthetic Minority Oversampling)
- XGBoost Model
- Hyperparameter tuning
- ROC Curve analysis
- Real-time fraud detection system

---

## Author

Conrad Allen C. Adajar,RCA – Data Science Portfolio Project
