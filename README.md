# Recommender Model for Customer Service Eligibility
## Project Overview
LangaSat, a satellite internet service provider, currently determines customer eligibility based solely on annual salary. However, it is believed that other factors may influence customer credit risk and eligibility.
This project involves developing an intelligent recommender model that accurately identifies customers eligible for the service using various factors beyond just salary.

This project follows the Cross-Industry Process for Data Mining (CRISP-DM) methodology, a widely adopted framework that ensures a structured and comprehensive approach to data science projects.

## Project Steps
### 1. Business Understanding
Objective: Develop a classification model to recommend eligible customers for the satellite service.
Stakeholders: LangaSat finanical management, data analytics team, marketing team.
Success Criteria: Accurate identification of eligible customers with a robust model that outperforms the current salary-based approach.

### 2. Data Understanding
Dataset: CustData2.csv containing customer details (e.g., job title, department, salary, year of birth, marital status, city of residence, years of residence, education level, occupation, household size).
#### Initial Analysis:
Identify data quality issues (e.g., missing values, duplicates, outliers).
Perform exploratory data analysis (EDA) using visualizations (correlation matrices, pair plots).
Document insights and correlations within the data.
#### PowerBi visuals that assisted in understanding the data
![powerbi1](https://github.com/user-attachments/assets/8444b4bf-6b02-43a4-ab69-9b2ff0922e74)
![powerbi2](https://github.com/user-attachments/assets/83b4e979-b39f-404c-b86d-f037c4de6eaa)
### 3. Data Preparation
#### Data Cleaning:
Handle missing values and remove duplicates. <br>
Address outliers and preprocess data as needed. <br>
#### Feature Engineering:
Encode categorical variables.<br>
Scale or discretize numerical features.<br>
#### Data Splitting:
Divide data into training and testing sets for model evaluation.<br>
### 4. Modelling
Model Selection:
Choose suitable classification algorithms (e.g., logistic regression, decision trees, random forest) based on data characteristics.<br>
#### Training:<br>
Train models using selected features, including variables other than annual salary.<br>
Fine-tune model parameters.<br>
Performance Metrics:<br>
Evaluate using metrics such as accuracy, precision, recall, F1-score.<br>
Visualization: <br>
Display confusion matrices and other performance metrics for clear interpretation. <br>
### 5. Model Evaluation
![modelacc](https://github.com/user-attachments/assets/56907df2-e22a-41fc-bc4f-33840b4e5696)
### 6. Deployment
![DashApp](https://github.com/user-attachments/assets/3d135744-dee6-46b0-bd7a-b7ae2ebee7eb)
