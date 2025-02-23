# phase-3-ml-project

# Project Overview
Project is lookign at building a predictive model for identifying customers at risk of churn for a telecommunications company. The dataset is analyzed and ML models used—Logistic Regression, Random Forest  and Decision Tree.

# Business Problem
Predict clients churn so as to have retention measures to avoid financial losses.
The stakeholders for this project include:
- Telecommunications company
- Business executives
- Customer Support
- Marketers
    
# Data Understanding

# Data source

The dataset for this project is taken from Kaggle competition. It has information on customers of a telecommunications company.

The purpose of this project is at retaining customers and so this dataset makes it suitable. In the dataset we have enough features to help in the prediction of customers churnning. We can create a predictive model which can help in creating retention strategies.

Let's look into the data by uderstanding its structure(shape). The dataset has (3333,21) rows, columns respectively.

In the code lets get an understanding of the first few rows and descriptive statistics of the data.

# Data Limitations.

Imbalances in the classes which gives biased models affecting the model training.

Missing data so as to not affect the quality of the data modelling.

Data won't account for seasonal trends or whether the market changes with new technologies.

# Jupyter Notebook
1. Data Preparation
   
   - Run EDA by checking for missing values, distributions and handling data.
     
   - Categorical encoding and creating new features if needed.
     
   - Splitting the data for the train and test splits.
     
2. Selecting a preference model
  We need to use between 2-3 classification models:

  - Baseline model: Here we shall choose to use Logistic Regression.
  - Non-parametric model: We introduce decision tree.
  - Ensemble model: Random forest
    
3. Model evaluation.
This is the final step on this notebook.

Metrics justification to real world.

The main objective in this project is to predict customers churning. Predicting the clients who are looking at churning helps to improve the retention and reduce the revenue loss and not tanish the telecom company reputation.

We shall be using the following metrics so as to evaluate the models performance so as to identify the most suitable;

Accuracy - This is how close a measurement is to the true or accepted value. Helps to understand overall correctness.
F1 Score - This is an evaluation metric that measures a model's accuracy. It combines the precision and recall scores of a model.
Precision - This how close measurements of the same item are to each other. Higher precission show less risk of retentions.
Recall - This is a performance metrics that apply to data retrieved from a collection, corpus or sample space. This will be used in idetifying the churners. High recall shows the clients that are most likely to churn.
There can be consequntial error when the model predicts a customer will churn however this doesn't happen, so this leads to waste of resource and retention measures which aren't needed this is a type I error.
# Evaluation
Model Performance evaluation.

Lets look into the performance with the current results.

Logistic Regression

Precision (Churn = 1): 0.53

Recall (Churn = 1): 0.18

F1-Score (Churn = 1): 0.27

Accuracy: 85.2%

Random Forest Classifier
Precision (Churn = 1): 0.96

Recall (Churn = 1): 0.65

F1-Score (Churn = 1): 0.78

Accuracy: 94.3%

Decision Tree Classifier
Precision (Churn = 1): 0.77

Recall (Churn = 1): 0.73

F1-Score (Churn = 1): 0.75

Accuracy: 92.7%

Selection of the final model: Looking into the 3 various models that we have used it is reasonable to say that the Random Forest is the most suitable based on its performance with an accuracy of 94.3% highest out of the models, precision of 0.96 and a recall of 0.65.

We used a holdout test data for all models and Random Forest had thee highest precision of 0.96 showing most of churners predicted here are churners in fact. However this model needs some more improvements as it misses about 35% of the actual churners in recall and a good F1 score of 0.78 showing a good stability between the precision and recall.

The model gives a strong tool for the prediction by identifying the at risk customers looking at churning. The precision results are signifacntly high showing we can trust the model predictions but the recall signifies that we could do more improvements.

In the future we can look at additional features to fine tune the model to get better recall value without affecting the precision.

Final, the model shows its able to address the real world problems in te telecommunications industry for the stakeholders.
# Improvements

  - Fine tuning the model by feature engineering can improve the model.
  - Monitoring the model.
  - Retrain the model over time to maintain its accuracy.

# Programming languages and models.
  - Python: Google Colab 
  - Machine Learning models: Logistic regression, decision tree and random forest.

# Author
Name: HABSHI PEDRO MWANGI
