# PassGuard: ML-Based Password Strength Predictor and Crack Time Estimator

This project uses machine learning to classify password strength and estimate crack time, providing users with actionable security feedback.

## Project Structure

PassGuard/
├── data/
│   └── passwords.csv
├── models/
│   └── model.pkl
├── notebooks/
│   └── PassGuard_Training.ipynb
├── app.py              ← Streamlit frontend
├── backend.py          ← ML logic
├── requirements.txt
└── README.md

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Dataset
- Download from Kaggle: https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset
- Place as `data/passwords.csv`

## Features
- 16 engineered features from raw passwords
- Multiple ML models compared (Random Forest, XGBoost, Logistic Regression, Gradient Boosting, SVM)
- Crack time estimation
- Black & white frontend (no color except for emoji icons)

## Author
Hajra Sarwar 
