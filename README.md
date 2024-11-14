# Salary Prediction Model Using Telco Customer Data

## Project Overview

In this project, a salary prediction model was developed using the WA_Fn-UseC_-Telco-Customer-Churn dataset, which contains information about customer behavior, demographic details, and service usage. The goal was to predict salaries based on customer data using machine learning algorithms.

## Approach

Two algorithms were employed for the salary prediction task:
- **Linear Regression (LR)**
- **Logistic Regression (LGBM)**
- 
![image](https://github.com/user-attachments/assets/71560d37-f901-4cd0-98fa-c968d84c9de4)
![image](https://github.com/user-attachments/assets/70e73f07-c0b2-4a9a-a9e8-c884534d254d)

The model development process involved several key steps:

1. **Model Training (with Null Values)**: Initially, both models were trained without removing null (missing) values to observe the effect of missing data on model performance.
   - **LR Base Error**
   - **LGBM Base Error**

2. **Handling Missing Values**: After removing null values, the models were retrained to assess the impact of null removal on performance.
   - **LR Error After Feature Engineering**
   - **LGBM Error After Feature Engineering**

3. **Hyperparameter Optimization**: Both models were fine-tuned by adjusting their hyperparameters, and the errors were recorded.
   - **LGBM Final Model Error**
   - **LGBM Null Model Error**

4. **Model Evaluation**: RMSE (Root Mean Squared Error) was calculated at each stage, and the model with the lowest RMSE value was applied to the project.

## Conclusion

![image](https://github.com/user-attachments/assets/96e2ee5c-e5cd-4b26-8d5f-a00bab42f932)

![image](https://github.com/user-attachments/assets/384a95f6-caa9-46e7-b1f2-69b77e7901e9)

![image](https://github.com/user-attachments/assets/c72435db-2c33-4cc5-989d-fd1652da285d)

![image](https://github.com/user-attachments/assets/18b0ff04-e0a5-4054-8306-15df6c1a8ea5)

![image](https://github.com/user-attachments/assets/bf50bf65-b820-41af-9214-2a2da8dadb2c)

This project successfully demonstrated how customer data in the telecommunications sector can be used for salary prediction. After feature engineering, handling missing data, and hyperparameter tuning, the model with the lowest RMSE value was applied to the project.





