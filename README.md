# Comparision of Different Machine Learning Models on Schizophrenia Detection

The purpose of this project to identify and compare how different models will predict whether a patient has schizophrenia or not based on FNC (functional network connectivity) features.Functional connectivity examines temporal statistical dependencies among distant brain regions by means of seed-based analysis or independent component analysis (ICA). Spatial ICA also makes it possible to investigate functional connectivity at the network level, termed functional network connectivity (FNC). 

Few classfication machine learning algorithms will be tested i.e Random Forest, Gradient Boosting, Support Vector Machine, K Nearest Neighbors, XGBoost
___
### About The Dataset

* Type of Machine Learning Method
    * Supervised Learning
        * Classfication
            * Random Forest
                * Accuracy - 77.57 % 
                * F1 Score - 75.00 %
                * Recall - 60.00 %
            * Gradient Boosting
                * Accuracy - 50%
                * F1 Score - 30.76%
                * Recall - 20%
            * Support Vector Machines
                * Accuracy - 72.22 %
                * F1 Score - 70.58 %
                * Recall - 60 %
            * KNN
                * Accuracy - 66.66 %
                * F1 Score - 66.66 %
                * Recall - 60 %
            * XGBoost
                * Accuracy - 66.66 %
                * F1 Score - 66.66 %
                * Recall - 60.00 %
___

### Steps to Solve Problem
* Import Dataset and Libraries
* Data Preprocessing
    * Train / Test Data split
    * Missing Data Imputation
    * Feature Scaling
* Model Build
    * Model Initiation and Fitting
    * Test predictions
* Model Perfromance
    * Recall
    * Case Prediction
        
