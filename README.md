#  Audiobook Churn Prediction

##  Project Overview
This project predicts whether a customer will churn (stop using the audiobook service) based on their usage and purchase behavior.

##  Dataset
- Features: Minutes_listened, Price_paid_overall, Book_length, Completion %, etc.
- Target: Churn (1 = churned, 0 = retained)

##  Steps in the Project
1. **EDA**: Understanding data distribution & patterns
2. **Data Cleaning**: Handle missing values, duplicates, outliers
3. **Feature Engineering**: Create Listening_Efficiency, Value_for_Money
4. **Data Preparation**: Train/test split, scaling
5. **Patterns & Insights**: Attrition rate analysis
6. **Model Training**: Logistic Regression, Random Forest, Gradient Boosting
7. **Feature Importance**: Key drivers of churn

##  Results
- Best Model: Random Forest (Accuracy = 85%, Recall = 78%)
- Top Features influencing churn:
  - Minutes listened
  - Completion rate
  - Value for money

##  Tech Stack
- Python
- Jupyter
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn
