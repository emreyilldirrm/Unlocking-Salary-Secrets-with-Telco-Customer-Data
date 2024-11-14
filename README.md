# Salary Prediction Model Using Telco Customer Data

## Project Overview

In this project, a salary prediction model was developed using the WA_Fn-UseC_-Telco-Customer-Churn dataset, which contains information about customer behavior, demographic details, and service usage. The goal was to predict salaries based on customer data using machine learning algorithms.

## Approach

Two algorithms were employed for the salary prediction task:
- **Linear Regression (LR)**
- **Logistic Regression (LGBM)**

  
![image](https://github.com/user-attachments/assets/94b76899-8d27-4e9b-93e6-048f044ac49a)
![image](https://github.com/user-attachments/assets/70e73f07-c0b2-4a9a-a9e8-c884534d254d)

The model development process involved several key steps:

1. **Model Training (with Null Values)**: Initially, both models were trained without removing null (missing) values to observe the effect of missing data on model performance.
   - **LR Base **
   - **LGBM Base **

2. **Handling Missing Values**: After removing null values, the models were retrained to assess the impact of null removal on performance.
   - **LR Error After Feature Engineering**
   - **LGBM Error After Feature Engineering**

3. **Hyperparameter Optimization**: Both models were fine-tuned by adjusting their hyperparameters, and the errors were recorded.
   - **LGBM Final Model **
   - **LGBM Null Model **

4. **Model Evaluation**: RMSE (Root Mean Squared Error) was calculated at each stage, and the model with the lowest RMSE value was applied to the project.

## Conclusion

*LR Base (NUll)**
![image](https://github.com/user-attachments/assets/69a76693-f327-42c2-9a4e-3ce1d6115f01)

**LGBM Base (Nulll)**
![image](https://github.com/user-attachments/assets/c5d8509d-3b42-4640-976a-829730a939f3)

**LR Error After Feature Engineering**
![image](https://github.com/user-attachments/assets/3f23365a-1d01-43fe-ae20-50dd23cb384f)

**LGBM Error After Feature Engineering**
![image](https://github.com/user-attachments/assets/3bcce0dd-5770-4630-95f0-b42fa8fa3480)

**LGBM Final Model **
**LGBM Null Model **
![image](https://github.com/user-attachments/assets/ff384928-5d5f-4370-99b2-e0b078f93196)

This project successfully demonstrated how customer data in the telecommunications sector can be used for salary prediction. After feature engineering, handling missing data, and hyperparameter tuning, the model with the lowest RMSE value was applied to the project.





