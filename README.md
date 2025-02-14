# Diabetes-prediction
# Objective
- To develop a machine learning model that can predict whether a person has diabetes based on medical parameters.
***DataSource:"https://github.com/roshni-1/Diabetes_prediction/blob/main/diabetes_data_upload.csv"***
#Problem Statement
- Diabetes is a chronic disease that requires early detection for effective management. This project aims to develop a machine learning model that predicts diabetes based on health parameters, enabling faster and more accurate diagnosis to support healthcare decision-making.
# steps Perform
1.Data collection & preprocessing
 - finding unique values in dataset (df.nunique())
 - finding null values and count them.
 - also describe summary of data. df.describe()
 -  To get information about data. df.info()
# EDA (Exploratory Data Analysis)
- Visualize distributions of key features.
- Identify correlations between variables.
- Finding the outliers
- perform Bivariate and Univariate analysis.
# Model Selection & Training
 - perform classification model:
    - accuracy, precision, recall, and F1-score.
- regression model:
     - calculate MSE,MAE,R2 etc
# Hyperparameter Tuning
- use Random Search for better performance.
# ANOVA
- To get get p-value.
# Feature Importance
- we use shap.
# Model Deployment
- use pickle file (.pkl) to create a new pickle file of our data
