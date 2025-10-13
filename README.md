# Credit Card Default Prediction

## Project Overview
This project predicts which credit card customers are likely to default on their payments. It helps financial institutions reduce losses and make better lending decisions using machine learning

## Business Problem
Credit card defaults cost banks billions annually. This system helps:
* Identify high risk customers before they default
* Reduce financial losses from bad debt
* Improve credit approval decisions
* Enable proactive customer management

## Dataset
UCI Credit Card Default dataset with:
* 30,000 customersfrom Taiwan
* 25 features including payment history, bill amounts, and demographic data
* 22.12% default rate (6,636 defaults)


## What this project does

### Data Preparation
* Combines and cleans customer data
* Handles missing values
* Creates new features like payment delays and credit utilization
* Encode cartegorical variables

### Data Analysis
* Shows default rate distribution (22.12% default rate)
* Compares customer segments by demographics
* Analyses payment behavior patterns
* Identifies risk factors
  
### Default Predidction
We test three different models:

* Logistic Regression (Traditional classification model)
    * Accuracy: 81.07%
    * Good for interpretability

* Random Forest (Ensemble tree-based model)
    * Accuracy: 80.10%
    * Best balance of precision and recall

* XGBoost (Advanced gradient boosting)
    * Accuracy: 79.88%
    * Strong predictive power

### Future Predictions

The model can classify new customers as high risk or low risk with confidence scores, enabling proactive risk management.

## Key Results

## Model Performance

| Model	| Accuracy	| Precision	| Recall	| F1-Score |
|-----------|-----------|-----------|-----------|-----------| 
| Logistic Regression	| 81.07%	| 64.36%	| 32.25%	| 42.97% |
| Random Forest	| 80.10%	| 56.30%	| 44.76%	| 49.87% |
| XGBoost	| 79.88%	| 55.87%	| 43.03%	| 48.62% |

## Business Insights

### Risk Factors
* Payment delays are the strongest predictors of default
* Recent payment behavior matters most for risk assessment
* Higher credit limits are associated with lower default risk

### Model Performance
* Random Forest performed best overall with 49.87% F1-Score
* Model achieves 75.4% ROC-AUC showing good predictive power
* Successfully identifies 45% of actual defaults while maintaining precision

### Customer Insights
* 22.12% of customers in the dataset defaulted
* Payment behavior is more important than demographic factors
* Consistent payment problems indicate higher default risk














