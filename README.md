**Credit Risk Predictor**
This project predicts whther a person has Good or Bad credit risk using Machine Learning

**What I Did:**

- Loaded the German credit dataset from Kaggle
- Cleaned the data (removed missing values)
- Did data analysis using graphs
- Converted text data into numbers (Label Encoding)
- Split data into training and testing sets
- Trained multiple models:
  Decision Tree
  Random Forest
  Extra Trees
  XGBoost
- Compared accuracy of all models
- Saved the best trained model
  **Best Accuracy: ~67% (XGBoost)**

**How to run:**

- git clone https://github.com/AsishChellamani/Credit-Risk-Predictor.git
- cd Credit-Risk-Predictor

- pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib

- python analysis_model.py
