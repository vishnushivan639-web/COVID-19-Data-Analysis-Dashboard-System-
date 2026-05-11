🏥 Healthcare Analytics Project
Predicting Diabetes Risk Using Machine Learning
📌 Overview

This project focuses on analyzing patient health metrics to predict the risk of diabetes using a structured and modular machine learning pipeline. The system is designed to be production-oriented, ensuring reproducibility, interpretability, and scalability.

The workflow includes:

Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Model training using a recall-optimized Random Forest
Standardized model evaluation
Optional prediction generation

The main goal is to develop a clinically meaningful model that minimizes false negatives, ensuring that diabetic patients are not missed.

📂 Dataset

Source: Public diabetes dataset inspired by the Pima Indians dataset

Description:
The dataset contains various health-related attributes of patients, including:

Glucose level
Blood pressure
BMI (Body Mass Index)
Insulin level
Age
Diabetes pedigree function
Outcome (Diabetic / Not Diabetic)
🎯 Objectives
Analyze patient health data and identify key predictors of diabetes
Build a machine learning model optimized for high recall
Follow a modular and production-style project structure
Provide clear evaluation metrics and insights
Create a scalable baseline for future healthcare analytics applications
⭐ Project Highlights
🧹 1. Data Preprocessing
Replaced non-physiological zero values with missing values
Applied median imputation to handle missing data
Ensured data consistency and quality
Centralized preprocessing logic in a modular structure
📊 2. Exploratory Data Analysis (EDA)
Analyzed feature distributions and relationships
Identified key predictors such as:
Glucose
BMI
Age
Diabetes pedigree function
Used visualization techniques to understand patterns and correlations
🤖 3. Machine Learning Model
Implemented a Random Forest Classifier
Used class weighting to handle data imbalance
Applied hyperparameter tuning using GridSearchCV with recall as the scoring metric
Developed training and evaluation pipelines
Saved the trained model for reuse
📈 4. Visualization

Visualization tools were used to evaluate and interpret the model:

ROC Curve → measures model performance
Feature Importance → identifies key influencing factors
Confusion Matrix → evaluates prediction accuracy
🛠️ Tools and Technologies
Python
pandas
<img width="1126" height="445" alt="line" src="https://github.com/user-attachments/assets/8d3a50f8-a501-433f-aa25-6e927dacb966" />
<img width="1134" height="420" alt="bar" src="https://github.com/user-attachments/assets/eda9a13c-7078-4a42-9ff7-401d7828adb3" />
<img width="1128" height="424" alt="scatter" src="https://github.com/user-attachments/assets/8471b6de-5932-4179-a949-28567ea03564" />



numpy
scikit-learn
matplotlib
joblib
argparse
Jupyter Notebook
