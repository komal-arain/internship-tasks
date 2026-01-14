# Task 4 – Predicting Insurance Claim Amounts

## Objective
The objective of this task is to predict medical insurance charges based on a person’s
age, BMI, smoking status, and other personal details.

---

## Dataset
The dataset used is the Medical Cost Personal Dataset. It contains the following columns:
- age  
- sex  
- bmi  
- children  
- smoker  
- region  
- charges  

The target variable is charges.

---

## Approach
1. Loaded the dataset using pandas  
2. Converted categorical columns into numerical values  
3. Performed exploratory data analysis using graphs  
4. Split the data into training and testing sets  
5. Trained a Linear Regression model  
6. Evaluated the model using MAE and RMSE  

---

## Results
The model shows that smoking, age, and BMI have a strong impact on insurance charges.
Smokers generally pay much higher medical costs compared to non-smokers.

---

## Conclusion
This project demonstrates how regression models can be used to estimate medical
insurance costs and understand the factors that influence them.
