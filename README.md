# DATA-SCIENCE-ML-Project
Cohort Analysis and Customer LTV for Gameflix
Here a Google doc link with detailed project explanation:
https://docs.google.com/document/d/17oA29cU-1_e9AYKp2wFoDtyPa7vfYvqA/edit?usp=sharing&ouid=103312074153672960540&rtpof=true&sd=true

CLTV TABLE(final_table)
https://drive.google.com/file/d/1-HXHNMKce3fs1gsw4nwu9k9Csgn84LSN/view?usp=sharing

🎓 Project Title: Predicting Graduate Admissions using Linear Regression
📄 View Full Project Report on Google Docs

📌 Overview
This project explores how we can predict the likelihood of a student being admitted to a graduate program using various academic and personal profile parameters. By applying linear regression techniques, we aim to identify the most impactful features on admission probability and build an interpretable and accurate model.

🔍 Problem Statement
The goal is to predict a student’s probability of admission (Chance of Admit) based on features like GRE score, TOEFL score, university rating, SOP and LOR strengths, CGPA, and research experience. This can help both students and educational consultants understand key factors influencing admissions and take data-driven decisions.

📊 Dataset Summary
Rows: 500

Features: GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research, Chance of Admit

No missing values or duplicates

Target variable: Chance of Admit (ranging from 0 to 1)

🧪 Steps Performed
1. Exploratory Data Analysis (EDA)
Univariate and bivariate visualizations for data distribution and relationships

Correlation matrix to identify strong predictors

Summary statistics (mean, min, max, std)

2. Data Preprocessing
Removed the 'Serial No.' column

Checked for and handled outliers using IQR

Confirmed no null or duplicate records

3. Model Building
Built a Multiple Linear Regression model using Statsmodels

Compared with Ridge and Lasso models using Scikit-learn

Interpreted coefficients, p-values, and model significance

4. Assumption Testing
Verified linearity, normality of residuals, homoscedasticity, and multicollinearity using:

Residual plots

QQ plots

Breusch-Pagan test

Variance Inflation Factor (VIF)

5. Model Evaluation
Used MAE, RMSE, R², and Adjusted R² for performance checks

Evaluated models on both training and test sets to avoid overfitting

📈 Key Insights
GRE, TOEFL, CGPA, and Research experience are strong predictors of admission chances.

LOR and SOP also contribute moderately.

Adding more features like internships, extracurriculars, or essay quality could further improve accuracy.

✅ Final Outcome
The model provides accurate, explainable predictions and offers actionable recommendations for students and consultants. It can be implemented into advisory tools or educational platforms to improve the graduate application process.

