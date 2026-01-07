# Churn Analysis and predictiom End-to-End Project
#### Overview <br>
This project provides a comprehensive end-to-end solution for analyzing and predicting customer churn.The primary goal is to empower businesses with data-driven insights to improve retention strategies and reduce revenue loss. The fictional IBM Telco dataset is used in this project. 
#### Problem Statement:<br> 
In the telecommunications industry, customer acquisition costs are 5–10 times higher than retention costs. Within the network service domain, churn is regarded as the rate at which customers stop doing business with the company or cancel their subscriptions, these customers could either be corporate or individuals. Churn in general could be from the company (e.g switch to competitor) or withdrawal from unappealing services with the same provider. Discontinuity or cancelation from customers adversely affects revenue and market share, thus, companies need to act proactively to limit these. The goal of this project is to build a model that enables the detection of high-risk customers before they leave so the company can implement targeted retention strategies.
#### Objectives:<br>
- Identify key drivers of customer churn
- Build a supervised churn prediction model
- Provide actionable business recommendations
### Dataset description and source
Dataset: IBM Telco Customer Churn Dataset (7,043 customers). Link  https://drive.google.com/file/d/1763OlxZ9Fun9-x3GYi6BUu_7ot9AfEkJ/view or sourced from Kaggle.<br>
Features include:
- Customer demographics
- Service subscriptions
- Contract and billing information
- **Target**: Churn (Yes, No)

#### Key Project Components<br>
- **Data Ingestion & Cleaning**: Raw data processing, handling missing values, and outlier detection to ensure high data quality.<br>
- **Exploratory Data Analysis (EDA)**: In-depth visualization of customer behavior patterns and correlation analysis between service features and churn.<br>
- **Feature Engineering**: Transformation of categorical variables and the creation of new predictive features to enhance model accuracy.<br>
- **Machine Learning Pipeline**: Implementation and comparative analysis of multiple classification models ( staring with Logistic Regression and Random Forest) to find the optimal predictor.
- **Evaluation & Insights**: Model performance assessment using accuracy, precision, recall, and AUC-ROC, followed by actionable business recommendations based on feature importance.


Outcome
The final deliverable includes a predictive model capable of identifying potential churners with high recall, alongside a breakdown of the specific factors (such as 
contract type or monthly charges) most likely to trigger a customer's departure. 
