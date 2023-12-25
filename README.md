README.md

*This README.md file provides a comprehensive overview of the customer churn prediction project, from data exploration and hypothesis testing to model development, evaluation, and deployment. It serves as a guide for users and stakeholders, summarising key findings and offering insights for business decision-making*

Predicting Customer Churn: A Data-Driven Approach


Introduction
Customer churn, the rate at which customers stop using a product or service, is a significant challenge for businesses. This project employs machine learning to predict and analyze customer churn, providing actionable insights for businesses. This README.md file summarizes key findings and concepts.

Project Overview
The project focuses on a telecommunications company, aiming to understand and predict customer churn. Following the CRISP-DM methodology, a machine-learning pipeline was developed for accurate churn prediction.

Data
Dataset: 5,000 records with attributes like gender, tenure, internet service type, payment method, and churn status.

Data Preparation: Rigorous cleaning and preprocessing ensured data reliability.

Exploration and Hypothesis
Data Understanding: Explored diverse customer information for a comprehensive view of behaviour.

Hypothesis: We tested the relationship between total charges and churn using Kruskal-Wallis test.


Research Questions and Recommendations


Internet Service Types (Q1):

Findings: DSL customers show higher loyalty, and fiber optic customers have significant churn.

Recommendations: Tailor strategies based on internet service type.


Having a Partner or Dependents (Q2):

Recommendations: Target marketing, enhance senior citizen programs, and promote partner-centric services.


Contract Types (Q3):

Recommendations: Promote long-term contracts, incentivize subscriptions, and transparent communication.


Payment Method (Q4):

Recommendations: Promote credit card usage, improve the electronic check process, and consider incentives for bank transfers.


Gender (Q5):

Recommendations: Tailor strategies, and improve overall churn management.


Hypothesis Testing Conclusion

Kruskal-Wallis test established a significant relationship between total charges and customer churn, allowing tailored retention strategies.


Data Preparation for Machine Learning

Pipeline: Meticulous cleaning, splitting data for training and testing.

Models: Decision Tree, Random Forest, SVM, Naive Bayes, Gradient Boosting.


Evaluation: Selected top three models: SVM, Random Forest, and Gradient Boosting.


ROC Curve Analysis: Identified Gradient Boost as the best-performing model.


Model Performance Metrics

Confusion Matrix:

True Positives (TP): 196

True Negatives (TN): 596

False Positives (FP): 144

False Negatives (FN): 71



Metrics:

Accuracy ≈ 78.3%

Precision ≈ 57.6%

Recall ≈ 73.4%

Specificity ≈ 80.5%

F1 Score ≈ 64.5%



Threshold Analysis

Explored ROC curves and thresholds for different models.

Considered trade-offs and business implications of threshold choices.



Hyperparameter Tuning

Conducted grid search for optimal hyperparameters.

Chose values for depth, split samples, number of trees, and feature selection.



Model Deployment

Set hyperparameters for the Gradient Boosting model.

Saved model and encoder for future use.



Model Utilization

We loaded the pre-trained model and encoder.

Preprocessed unknown data and made predictions.



Business Implications

Operationalizing the Model: Predictions can support real-world decision-making.

Continuous Monitoring: Ongoing evaluation and feedback loop for model improvement.


Decision Support: Predictions can be used for targeted actions to minimize churn or address specific business objectives.


Key Libraries Used;

matplotlib                3.8.0 --For visualizations

numpy                     1.25.2 --For data manipulation

pandas                    2.1.0 --For data manipulation

seaborn                   0.13.0 --For visualizations

scipy                     1.11.3 --For statistical analysis

sklearn                   0.0.post9 --Machine learning Packages