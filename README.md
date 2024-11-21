## Bank Marketing Prediction Project
This project applies predictive analytics techniques to the Bank Marketing dataset to determine the likelihood of customers subscribing to a term deposit. By leveraging Logistic Regression and Decision Tree Classifiers, this analysis provides insights into customer behavior and enables data-driven decision-making.

https://archive.ics.uci.edu/dataset/222/bank+marketing

**Overview**
The dataset originates from a Portuguese banking institution's marketing campaigns, consisting of client data and campaign outcomes. The project focuses on binary classification, where the target variable is whether a client subscribes to a term deposit (yes/no).

**There are four datasets:** 

1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010).
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs). 
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). 
 

* Dataset Characteristics: Multivariate               
* Subject Area: Business        
* Feature Type: Categorical, Integer                
* Instances: 45211           
* Features: 16

**Key Objectives**
* Explore and preprocess the dataset for optimal performance.
* Build and evaluate predictive models using Logistic Regression and Decision Trees.
* Compare model performance and provide actionable insights.
  
**Techniques and Tools**
* Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
* Logistic Regression: For baseline predictive modeling and interpretability.
* Decision Tree Classifier: For a more flexible, non-linear model that captures complex relationships.
* Performance Evaluation: Using accuracy, precision, recall, F1-score, and ROC-AUC metrics.

**Results and Findings**
* The Logistic Regression model provided insights into the key factors influencing customer decisions, emphasizing simplicity and interpretability.
* The Decision Tree model offered higher flexibility, capturing non-linear relationships for improved predictive power in certain scenarios.


The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 


