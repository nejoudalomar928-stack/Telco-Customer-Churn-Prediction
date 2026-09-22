# Customer Churn Prediction
Project Overview
This project uses machine learning to predict customer churn based on customer demographic, service, contract, and billing 
information.

The project includes data exploration, preprocessing, visualization, machine learning, hyperparameter tuning, and model evaluation.

##Dataset
The dataset contains 7,043 customer records and 21 columns.
The target variable is Churn, which indicates whether a customer churned.
Data Preprocessing
The following steps were performed:
- Converted TotalCharges to numeric.
- Removed the customerID column.
- Encoded the target variable.
- Applied one-hot encoding to categorical variables.
- Applied feature scaling where needed.
Machine Learning Models
The following classification models were used:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
Hyperparameter tuning was also performed using GridSearchCV.
Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
Project File
MLPh2final.ipynb contains the complete analysis, preprocessing, visualizations, machine learning models, tuning, and evaluation.
