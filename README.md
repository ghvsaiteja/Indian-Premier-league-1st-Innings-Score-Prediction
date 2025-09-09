# Indian-Premier-league-1st-Innings-Score-Prediction
A machine learning project that predicts the first innings score of IPL matches based on historical match data.  Built using Python, Pandas, and Scikit-learn  Includes data preprocessing, feature engineering, and model training  Jupyter Notebook with step-by-step workflow

This project predicts the first innings score of IPL matches using machine learning models. It takes historical IPL match data, processes it, and builds a model that can estimate the likely first innings score based on match conditions.

**Project Overview**

Worked on IPL dataset containing match details and performance stats
Cleaned and preprocessed the data for better model accuracy
Built and tested different ML models for score prediction
Evaluated model performance using metrics like R² score and Mean Absolute Error
Final model can predict the first innings total with reasonable accuracy

**Workflow**
**Data Loading** → Read ipl.csv file
**EDA (Exploratory Data Analysis)** → Analyze teams, venues, runs, wickets
**Feature Engineering** → Convert categorical data, create useful features
**Model Training** → Train ML models (Linear Regression, Random Forest, etc.)
**Evaluation** → Check accuracy with test data
**Prediction** → Enter match inputs → get predicted 1st innings score

**Results**

Models tested: Linear Regression, Decision Tree, Random Forest
Random Forest performed best with lowest error margin
Predictions are close to actual scores in most cases

**Future Improvements**

Add second innings win probability prediction
Train on updated IPL datasets (2023/2024 seasons)
Deploy as a web app with Streamlit/Flask
