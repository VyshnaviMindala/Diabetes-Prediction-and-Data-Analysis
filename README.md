# Diabetes Prediction and Data Analysis Project

## Project Description:
This project aims to predict diabetes and conduct data analysis using various health indicators. The dataset includes important features like glucose levels, blood pressure, insulin, BMI, and more, which are used to answer specific research questions and uncover trends related to diabetes. The Random Forest algorithm was applied for prediction, and it achieved an accuracy of 99%.

## Dataset:
The dataset used in this project is `diabetes.csv` and contains the following columns:

- **Pregnancies**: Number of pregnancies
- **Glucose**: Glucose level in the blood
- **BloodPressure**: Blood pressure measurements
- **SkinThickness**: Thickness of the skin
- **Insulin**: Insulin levels in the blood
- **BMI**: Body Mass Index
- **DiabetesPedigreeFunction**: A function that represents the likelihood of diabetes based on family history
- **Age**: Age of the individuals
- **Outcome**: The final result, where 1 indicates diabetes and 0 indicates no diabetes

## Research Questions:
The following questions were explored during the data analysis:

1. What is the distribution of the 'Pregnancies' column?
2. How does the 'Glucose' level vary across different outcomes?
3. Is there a correlation between 'SkinThickness' and 'BMI'?
4. What is the average 'BloodPressure' of individuals with diabetes ('Outcome' = 1)?
5. What is the median 'Insulin' level for individuals without diabetes ('Outcome' = 0)?
6. How does the 'DiabetesPedigreeFunction' differ between age groups?
7. What is the age distribution of the individuals in the dataset?
8. What percentage of individuals in the dataset have diabetes ('Outcome' = 1)?
9. How is 'BMI' distributed across different numbers of 'Pregnancies'?
10. What is the average age of individuals with the highest 'Glucose' level?
11. Is there any relationship between 'Insulin' levels and 'BMI'?
12. What is the correlation between 'Age' and 'DiabetesPedigreeFunction'?
13. How does 'BloodPressure' vary with increasing 'Age'?
14. What is the distribution of 'Pregnancies' among individuals with diabetes?
15. How are 'Age' and 'BMI' related in terms of diabetes diagnosis?
16. Is there a trend in 'Glucose' levels based on the 'Pregnancies' count?
17. What is the average 'Insulin' level for different age groups?
18. How does 'SkinThickness' compare between individuals with and without diabetes?
19. What is the average 'DiabetesPedigreeFunction' for different 'BMI' ranges?
20. Are older individuals more likely to have diabetes ('Outcome' = 1)?

## Algorithm Used:
The Random Forest algorithm was used to predict diabetes. After training and testing the model, it achieved an accuracy of 99%.

## Files in the Repository:
- **diabetes.csv**: The dataset used for both analysis and prediction.
- **Diabetes_Data_Analysis_Project.ipynb**: Jupyter Notebook containing the data analysis, visualizations, and implementation of the Random Forest algorithm for prediction.
- **README.md**: Documentation of the project.

---

This repository showcases how machine learning, specifically the Random Forest algorithm, can be applied in the healthcare domain to predict diabetes and analyze key health metrics. Explore the notebook for a detailed breakdown of the analysis and insights derived from the data.
