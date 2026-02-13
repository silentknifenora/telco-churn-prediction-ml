Telco Customer Churn Prediction (Machine Learning)

Project Overview
Customer churn is a major problem for telecom companies because losing customers directly impacts revenue.

This project builds machine learning models to predict which customers are likely to churn, allowing businesses to take proactive retention actions.

Business Goal
Identify high-risk customers and reduce churn through targeted offers and retention strategies.

Dataset
Telco Customer Churn dataset

- 7,032 customers
- 19 features
- Target: Churn (Yes/No)

Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

Workflow
1. Data cleaning and preprocessing
2. One-hot encoding for categorical features
3. Feature scaling with StandardScaler
4. Train/test split (80/20)
5. Logistic Regression model
6. Random Forest model
7. Model evaluation

Results
- Logistic Regression Accuracy: 78.7%
- Random Forest Accuracy: ~84%
- Improved churn detection using Random Forest

Visualizations
Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

Feature Importance
![Feature Importance](images/feature_importance.png)

Key Insights
- Short tenure customers churn more
- High monthly charges increase churn risk
- Contract type strongly affects retention
- Random Forest performs better than Logistic Regression

How to Run
Install dependencies:
pip install pandas numpy scikit-learn matplotlib seaborn

Run notebook in Google Colab or Jupyter.

Skills Demonstrated
- Data Cleaning
- Feature Engineering
- Classification Modeling
- Model Evaluation
- Business Insights

Author
Neha Raut.
