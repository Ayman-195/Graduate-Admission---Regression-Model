Graduate Admission Prediction
Overview
This project aims to predict the chances of admission to a master's program based on various factors from an Indian perspective. The dataset includes:

GRE Scores (out of 340)
TOEFL Scores (out of 120)
University Rating (out of 5)
Statement of Purpose (SOP) and Letter of Recommendation (LOR) Strength (out of 5)
Undergraduate GPA (CGPA) (out of 10)
Research Experience (binary: 0 or 1)
Chance of Admit (ranging from 0 to 1)
The goal is to predict the probability of admission and identify which factors are most significant in the admission decision.

Contents
Introduction
Importing Libraries
Loading the Data
Data Cleaning
Data Preprocessing
Regression Models
Linear Regression Model
Polynomial Regression Model
SVM Model
KNN Model
Decision Tree Model
Random Forest Model
XGBoost Model
Data Profiling
Conclusion
Conclusion
In our regression analysis, we evaluated several models: Linear Regression, Polynomial Regression, K-Nearest Neighbors (KNN), Decision Tree Regression (DT), Random Forest Regression, and XGBoost Regression (XGB). As expected, the Linear Regression model performed the best, effectively capturing the relationships in the data. The most influential factor was CGPA, indicating its strong impact on the likelihood of admission, while University Rating was the least significant. This underscores the suitability of the Linear Regression model and highlights the importance of CGPA.
