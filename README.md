# Superkart_ML_deploy_g

Project Overview 

 SuperKart, a retail chain with multiple outlets across various city tiers, needed a solution to accurately forecast quarterly sales revenue. Their goal was to optimize inventory management and enhance planning by using a data-driven predictive model that could be used in real-time across departments.

Objective

Designing and deploying a machine learning-based forecasting solution using historical sales data. This included data preparation, model development, hyperparameter tuning, and creating a user-friendly deployment interface for non-technical users.

Approach & Implementation

1. Data Understanding and EDA:


Imported historical sales data and performed univariate and bivariate analysis.


Identified patterns in sales based on regions, product categories, and time periods.


2. Data Preprocessing:


Created a preprocessing pipeline including encoding, scaling, and feature engineering.


Wrote utility functions to clean and transform the data for model readiness.


3. Modeling and Tuning:


Built both Random Forest and XGBoost Regressor models.


Performed hyperparameter tuning using GridSearchCV to maximize performance metrics.


Compared model performance using RMSE and R² scores.


4. Model Deployment:


Serialized the best-performing model using Joblib.


Built a Flask backend API to serve predictions.


Wrote a Dockerfile and hosted the backend on Hugging Face Spaces.


5. Frontend Development:


Created an interactive Streamlit frontend to allow users to input parameters.


Integrated the frontend with the Flask API for real-time prediction.


Deployed the frontend separately, ensuring seamless communication between both ends.


Result:

Delivered a real-time sales forecasting tool accessible across SuperKart’s departments.


Enabled regional planners to make data-driven decisions, reducing overstock and stockouts.


Improved quarterly forecast accuracy significantly through model tuning and robust architecture.


The interactive UI empowered non-technical staff to independently use the tool, boosting adoption.


Deployment to Hugging Face Spaces ensured scalability, portability, and ease of maintenance.
