
## Repository Structure

The following documents are for Phase 3 Project:

```
├── README.md                           <- The top-level README for reviewers of this Phase 3 project
├── Phase3_project.ipynb       			<- Jupyter notebook analysis
├── Project3_Presentation.pdf     		<- PDF Presentation 
├── data                          		<- Sources of the datasets
|-- 
```


# Project 3: User Churn Prediction

**Authors**: Liang

## Overview

The Project is to provide business insigts to the business stakeholder about if the customers would churn and stop the business connection with the company

The project has utilized public data to analyze customer churn in the SyriaTel telecommunications company. Based upon the findings about Customer Churn and the factors leading to the action, recommendatios are given to the stakerholders

## Business Problem

A telecommunications company provides telephone service to customers. They would like to investigate further insights about customer churn and the factors leading to the actions.

We work on this project to provide insights to this telecommunications company

Business insights to investigate:

Predict if a customer will soon churn and stop the service
What factors or any predictable patterns are affecting the customer churn actions ?


## Data

Sources:
Dataset of SyriaTel Telecommunications Company through Kaggle Competition
`bigml_59c28831336c6604c800002a.csv`


## Methods

Classification Modeling Analysis 
Train Classification Models for User Churn Predictions and feature importance analysis


## Results

Model Performance 
	Accuracy :  >0.9
	Precision/Recall : 0.95, 0.86
	ROC Aera under Curve : 0.91



Feature Importance

1. feature 2 total day minutes: 0.152388
2. feature 4 total day charge: 0.140177
3. feature 14 customer service calls: 0.123639
4. feature 15 international_plan_encoded: 0.094776
5. feature 5 total eve minutes: 0.069128
6. feature 7 total eve charge: 0.061867
7. feature 12 total intl calls: 0.047132
8. feature 13 total intl charge: 0.043996
9. feature 11 total intl minutes: 0.039468
10. feature 8 total night minutes: 0.038498
11. feature 10 total night charge: 0.034284
12. feature 9 total night calls: 0.029350
13. feature 1 number vmail messages: 0.027603
14. feature 3 total day calls: 0.026368
15. feature 0 account length: 0.026201
16. feature 6 total eve calls: 0.025031
17. feature 16 voice_mail_plan_encoded: 0.020095

## Conclusions

Classification models for User Churn Prediction
1. Model prediction for binary classification outcome 
2. Relevant features affecting user decisions



## For More Information

Please review our full analysis in [our Jupyter Notebook](./Phase3_project.ipynb) or our [presentation](./Project3_Presentation.pdf).


