# Wine-Store-Employee-Retention-Analysis

## Overview
This project aims to analyze and predict employee retention for a fictitious wine store. The analysis is based on a dataset containing various attributes related to employees, such as their roles, the number of sales they made, and other factors. The goal is to identify key factors influencing employee turnover and to develop a predictive model to help the store manage employee retention more effectively.

## Project Structure
- **Final_Wine_Store_Employee_Retention_Analysis.ipynb**: The Jupyter notebook containing all the code and analysis steps.

## Analysis Steps
1. **Data Cleaning**: Handling missing values, removing irrelevant columns, and ensuring data types are appropriate.
2. **Exploratory Data Analysis (EDA)**: Exploring relationships between different features and the target variable (employee retention).
3. **Feature Engineering**: Creating new features, encoding categorical variables, and addressing multicollinearity.
4. **Feature Selection**: Identifying the most relevant features for the predictive model.
5. **Modeling**: Building and fine-tuning various machine learning models to predict employee retention.
6. **Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

## Key Findings
- The analysis conducted on the wine store's employee data has yielded several significant insights:

1. **Key Factors Influencing Retention**:
The most critical features influencing employee retention were identified as satisfaction_level, years_at_company and last_performance_evaluation.
High satisfaction_level and longer years_at_company are associated with higher retention rates, whereas low satisfaction_level correlates with higher turnover.
2. **Model Performance**:
The Random Forest model, after fine-tuning, achieved the highest performance metrics with an accuracy of 98.49%, a precision of 98.93%, a recall of 94.86%, and a ROC-AUC score of 97.26%.
The Gradient Boosting model also performed well, with slightly lower but still robust metrics.
3. **Predictive Capabilities**:
The models can accurately predict which employees are at risk of leaving, enabling the wine store to take proactive measures to retain valuable staff.

## Tools and Libraries Used
- **Python**: Programming language used for the analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning models and evaluation.
