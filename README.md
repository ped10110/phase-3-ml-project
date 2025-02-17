# phase-3-ml-project

# Project Overview
This is a project for identifying the contributor to car accidents in chicago based on car, passenger or roads by using a predictor. 
We are looking for reasonable insights for our stakeholders at Vehicle Safety Board to use the predictive factors to ensure road safety.

# Business Problem
Car accidents don't only affect loss of life but also economic losses for repairing the car or damage to city property.
This ML predictions helps us in identifying patterns to avoid or reduce further accidents happening on the road.
Identifying these key patterns can help in:

  - Better traffic regulation by the city
  
  - Train the police sector on accident areas
    
# Dataset
The dataset I will be using for this project is the Chichago Car Crashes.
This dataset has information on vehicle data(type,damage,year), driver/passenger data(age,gender,safety) and the weather condition on different occassions when accidents happened.
Build a classifier to predict the primary contributory cause of a car accident, given information about the car, the people in the car, the road conditions etc. You might imagine your audience as a Vehicle Safety Board who's interested in reducing traffic accidents, or as the City of Chicago who's interested in becoming aware of any interesting patterns.

# Jupyter Notebook
1. Data Preparation
   
   - Run EDA by checking for missing values, distributions and handling data.
     
   - Categorical encoding and creating new features if needed.
     
   - Splitting the data for the train and test splits.
     
2. Selecting a preference model
  We need to use between 2-3 classification models:

  - Baseline model: Here we shall choose to use Logistic Rgression.
  - Non-parametric model: We introduce decision tree.
  - Ensemble model: Random forest
    
3. Model assessment
  The performance made by the models needs to be evaluated by accuracy and Precision.
  - Accuracy: Measure of how the model can make relevant predictions using the data. 
  - Precision and f1-score: This is for data concerns.
# Key Findings
  - The top causes for accidents are; speeding and weather conditions.
  - Decision trees performed extremely well but were prone to overfitting.
  - Random forest was the model that was most suitable by giving a good accuracy.
  - Analysis shows we need to focus on conditions on the road and behavioral issues by drivers as factors.
# Improvements

  - Pickup more data.
  - Include external datasets with real time weather reports as this is a big factor in the accidents.
  - Design a predictive app for real time assessments.
# Structure
├── data/                  # Raw & processed datasets

├── notebooks/             # Jupyter Notebooks for EDA & modeling

├── models/                # Trained models and results

├── src/                   # Python scripts for data processing & training

├── README.md              # Project documentation

# Programming languages and models.
  - Python: Jupyter notebook 
  - Machine Learning models: Logistic regression, decision tree and random forest.

# Author
Name: HABSHI PEDRO MWANGI
