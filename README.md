# -Machine-Learning-Pipeline-Data-Imputation-Scaling-and-Classification-for-Diabetes-Prediction
This project aims to predict diabetes onset by building a machine learning model that preprocesses and prepares the data using several steps, including missing value imputation, data scaling, and classification model training

Steps
Data Cleaning and Missing Value Imputation

Missing values in the dataset are filled using a Random Forest model. The model leverages the existing values of other features to predict and impute missing entries in columns such as Glucose, BloodPressure, and BMI. This process helps to retain as much data as possible for accurate training.
Feature Scaling

To ensure that all features contribute equally to the model and improve its learning process, StandardScaler is used to standardize the data. This scaling method centers the features by removing the mean and scales them to unit variance, resulting in a mean of 0 and a standard deviation of 1.
Model Training and Prediction

After preprocessing, the data is fed into a Logistic Regression model to predict the likelihood of diabetes onset. Logistic Regression is used as the classification model to distinguish between diabetic and non-diabetic cases. The model is trained on the preprocessed data and evaluated on a test set to measure its accuracy.

