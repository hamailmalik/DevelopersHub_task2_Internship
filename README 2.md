Readme.txt for task 2
# End-to-End Machine Learning Pipeline for Customer Churn Prediction

##  Objective

The objective of this project is to build a reusable and production-ready machine learning pipeline to predict customer churn using the Telco Customer Churn dataset.

The project demonstrates data preprocessing, feature engineering, model training, hyperparameter tuning, and model deployment preparation.

---

##  Dataset

**Telco Customer Churn Dataset**

The dataset contains customer demographic information, account details, subscribed services, and churn status.

Target Variable:

- Churn (Yes / No)

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

##  Methodology

1. Loaded the dataset.
2. Performed data cleaning.
3. Handled missing values.
4. Encoded categorical features.
5. Standardized numerical features.
6. Built preprocessing pipelines using Pipeline and ColumnTransformer.
7. Trained Logistic Regression and Random Forest models.
8. Applied GridSearchCV for hyperparameter tuning.
9. Compared model performance.
10. Exported the best model using Joblib.

---

##  Evaluation Metrics

- Accuracy
- Classification Report
- Precision
- Recall
- F1-score

---

## Project Structure

```
Task_2_End_to_End_ML_Pipeline/
│
├── Task_2_End_to_End_ML_Pipeline.ipynb
├── churn_pipeline.joblib
├── README.md
└── requirements.txt
```

---

##  Key Results

- Developed a reusable ML pipeline.
- Implemented hyperparameter tuning using GridSearchCV.
- Exported the trained model for deployment.
- Compared multiple classification algorithms.

---

## Skills Gained

- Data Preprocessing
- Feature Engineering
- Machine Learning Pipelines
- Hyperparameter Optimization
- Model Serialization
- Production-ready ML Workflow

---

## Author

Developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.
