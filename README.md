# Machine-Learning-Model-for-Predicting-Customer-Churn-

Languages/Libraries: Python, Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib
Techniques: Data Preprocessing, EDA, SMOTE Oversampling, Supervised ML (Classification)

This project focuses on predicting customer churn using machine learning techniques. The dataset is sourced from Kaggle and contains customer demographics, account details, and service usage information. The aim is to identify customers likely to discontinue services and provide actionable insights for retention strategies.

*Project Workflow*

1. Data Preprocessing

Removed irrelevant columns (e.g., customerID).
Handled missing values in TotalCharges by replacing blanks with 0 and converting to numeric.
Encoded categorical features using LabelEncoder.
Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique).

2. Exploratory Data Analysis (EDA)

Distribution analysis of numerical features (tenure, MonthlyCharges, TotalCharges).
Visualized categorical variables and churn distribution.
Identified imbalanced churn ratio.

3. Model Development

Implemented multiple models:
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Compared models based on accuracy, confusion matrix, and classification report.

4. Results & Final Prediction

XGBoost gave the best performance with the highest accuracy and balanced precision-recall.
The final model predicts whether a customer will Churn (Yes/No) based on their profile.
Sample prediction: A customer with low tenure and high monthly charges was correctly predicted as likely to churn.

5. Deployment Preparation

Final XGBoost model saved as a .pkl file using pickle for future deployment.

6. Outcomes

Built an end-to-end pipeline for churn prediction.
Provided insights into key drivers of churn.
Delivered a deployable ML model that can predict if a given customer will churn.
