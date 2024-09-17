# Graduate Admission Prediction

## Overview
This project focuses on predicting the chances of admission to a master's program using various regression models. The dataset used for this analysis includes the following parameters:

- **GRE Scores** (out of 340)
- **TOEFL Scores** (out of 120)
- **University Rating** (out of 5)
- **Statement of Purpose (SOP) and Letter of Recommendation (LOR) Strength** (out of 5)
- **Undergraduate GPA (CGPA)** (out of 10)
- **Research Experience** (binary: 0 or 1)
- **Chance of Admit** (ranging from 0 to 1)

The goal is to predict the probability of admission based on these factors and identify which factors play a more significant role in the admission decision.

[For more information]([https://www.openai.com](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions/data))

## Contents
- **Introduction**
- **Importing Libraries**
- **Loading the Data**
- **Data Cleaning**
- **Data Preprocessing**
- **Regression Models**
  - Linear Regression Model
  - Polynomial Regression Model
  - SVM Model
  - KNN Model
  - Decision Tree Model
  - Random Forest Model
  - XGBoost Model
- **Data Profiling**
- **Conclusion**

## Conclusion
In our regression analysis, various models were evaluated, including **Linear Regression**, **Polynomial Regression**, **K-Nearest Neighbors (KNN)**, **Decision Tree Regression (DT)**, **Random Forest Regression**, and **XGBoost Regression (XGB)**. As expected, the **Linear Regression** model emerged as the best performer, demonstrating its effectiveness in capturing the underlying relationships in the data. The most influential factor in the predictions was **CGPA**, reflecting its strong impact on the outcome, while **University Rating** proved to be the least significant feature. This reinforces the suitability of the Linear Regression model and underscores the importance of CGPA in predicting the probability of admission.

![Data](https://cityupload.io/2024/09/4-data.png)
![Feature Importance](https://cityupload.io/2024/09/feature-importance.png)
![heatmap](https://cityupload.io/2024/09/heatmap.png)
