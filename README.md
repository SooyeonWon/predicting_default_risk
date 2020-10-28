# Predicting Default Risk - Creditworthiness
Classification Modelling and Performance Comparison

#### by Sooyeon Won 

### Keywords 
- Analytical Framework
- Supervised Learning 
- Binary Classification Models 
  - Logistic Regression Model
  - Decision Tree Model 
  - Random Forest Model
  - Gradient Boosting Model
  - AdaBoost Model
- ROC curve 
- K-fold cross-validation
- Model Selection and its Application

### Summary of Findings

A bank recently received an influx of loan applications. I built and apply different classification models to provide an appropriate recommendation. Among the various models, I found out that Random Forest Model is the most suitable for predicting the creditworthiness of credit applicants. Based on the Random Forest model, I concluded 408 customers belong to the segment 'Creditworthy’.

This analysis is separated into three parts.
1. The first part of the analysis (Filename: 01_Creditworthiness_Data_Cleaning_Exploration.ipynb) contains the process of Data Cleaning and Data Exploration with appropriate visualizations. At the end of the Part1, I select the features associated with the creditworthiness of customers, which is the target variable of the analysis.
2. In the second part of the analysis (Filename: 02_Creditworthiness_Data_Analysis.ipynb), I trained the dataset with various classification models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosted Model, and AdaBoost Model. Then they are validated with the test dataset. Additionally, I evaluate the performance of the models with k-fold cross validation techniques.
3. After selecting the model with best performance, I conclude that how many new credit applicants are classified as creditworthy customers.

### References 

[Logistic Regression (aka logit, MaxEnt) classifier - sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)<br>
[How to Calculate Feature Importance With Python](https://machinelearningmastery.com/calculate-feature-importance-with-python/)<br>
[Decision Tree Classifier - sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)<br>
[Categorical Features and Encoding in Decision Trees](https://medium.com/data-design/visiting-categorical-features-and-encoding-in-decision-trees-53400fa65931)<br> 


