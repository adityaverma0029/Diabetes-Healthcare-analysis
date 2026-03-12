# **Healthcare Readmission Analytics Project**  
</br>
**Project Overview**  
This project provides an end-to-end data science pipeline to analyze and predict hospital readmissions for patients with diabetes. Using a dataset of over 100,000 hospital admissions from 130 US hospitals (1999-2008), the project identifies key risk factors and builds predictive models to help healthcare providers reduce readmission rates and improve patient outcomes.    
</br> </br>  **Features**  
-Automated Data Acquisition: Integrated instructions and scripts for downloading the UCI Diabetes dataset.   
-Comprehensive Preprocessing: Handles missing values (represented as '?'), cleans categorical features, and performs feature engineering.  
-Exploratory Data Analysis (EDA): Visualizes patient demographics, admission types, and the impact of various medications on readmission.  
-Predictive Modeling: Implements multiple machine learning algorithms including Random Forest and Logistic Regression.  
-Business Impact Analysis: Calculates potential cost savings and identifies high-risk patients for clinical intervention.  
</br>
**Tech Stack**</br> Python 3(Pandas, NumPy) </br> Visualization-(Matplotlib, Seaborn) </br> Machine Learning-(Scikit-Learn) </br> Environment-Jupyter Notebook    
</br>
</br>
**Project Workflow**  
-Environment Setup: Loading essential libraries and configuring plotting styles.  
-Data Acquisition: Loading the 101,766-row dataset.  
-Data Preprocessing: Cleaning data, handling 50 different columns of patient information, and preparing features for modeling.  
-Modeling: Training classifiers to distinguish between readmitted and non-readmitted patients.  
-Evaluation: Using ROC-AUC, Precision, Recall, and F1-score to validate model performance.  </br>
</br>**Key Insights & Impact**  
-Risk Identification: The model successfully identifies high-risk patients who are likely to be readmitted within 30 days.  
-Cost Savings: Provides a framework for calculating the net benefit of preventative interventions.
-Clinical Recommendations: Offers actionable insights based on patient demographics and medical history.
