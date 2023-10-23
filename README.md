# SyriaTel Customer Churn Analysis
![Pic](https://img.freepik.com/free-photo/futuristic-smart-city-with-5g-global-network-technology_53876-98438.jpg?w=900&t=st=1698041672~exp=1698042272~hmac=e0ad7bd524a30c25c7fc7a623f3001ff863be7c4ba8ef777eecbdf80e909ecba)

## Project Overview
SyriaTel, a leading telecommunications company, is facing a significant challenge with customer churn. Churn is when customers decide to terminate their subscriptions with SyriaTel, resulting in revenue loss. To address this issue, SyriaTel aims to build a predictive model to identify customers who are likely to churn. By proactively targeting these at-risk customers with retention strategies, SyriaTel hopes to reduce churn rates and retain valuable customers.
## Problem Statement 
"Can we predict customer churn for SyriaTel and identify the key factors driving churn, enabling the company to implement effective retention strategies?"

## Data Science Process Used:
The Data Science Process that is adhered to in this analysis is the CRISP-DM Process.

### 1. Business Understanding
Telecoms prioritize acquiring and retaining subscribers. Customer attrition is a major concern in the competitive telecom sector, impacting companies like Syriatel. To address churn effectively, telecom businesses must recognize its underlying factors and predict them accurately. Businesses can proactively identify customers at risk of leaving and devise personalized retention strategies. Proactive churn management reduces revenue losses and improves customer satisfaction.


### 2. Data Understanding

##### What Data Did We Use?
The SyriaTel Dataset was retrieved from [Kaggle](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset). It contains information on customers. The data includes various details like the state the customer is from, how long they've been a customer, whether they have an international plan or voice mail plan, how many customer service calls they've made, and many more.

### 3. Data Preparation:
In this stage, data is transformed, cleaned, and preprocessed to make it suitable for analysis. This included;
* Data Type conversion, Dealing with multicollinearity, and splitting the data.
  
### 4. Modeling

We tested our model to see how well it could predict customer churn. We fitted four models, Decision trees, Random forests, Logistic regression, and Gradient boost model. Our best model was the Gradient Boost Classifier, which had a recall score of about 81.2%.

##### Model Evaluation:

A combination of metrics such as accuracy, precision, recall, F1-score, and ROC- AUC can be used to evaluate the performance of the model and ensure that it meets the business requirements and goals of the telecom company.

The Gradient Boosting model demonstrates excellent performance with an accuracy of 96.08% and a balanced F1-score of 85.87%, indicating effective identification of churn cases while minimizing false positives.


Additionally, the key features that were shown to influence whether a customer would churn or not can be seen in the bar plot displayed below. We can note that the total expenditure is a key predicting variable.

## Conclusions 
Factors such as the number of customer service calls, whether the customer has an international plan, and the total day's minutes and charges were significant predictors of customer churn. Interestingly, we found that customers with an international plan are more likely to churn.

### What's Next?
Based on our findings, we recommend SyriaTel to:
- **Review International Plan:** Review the structure and pricing of the international plan to ensure it meets customer needs.

- **Improve Customer Service:** Improve the customer service experience to reduce the likelihood of churn.

- **Analyze Pricing Structure:** A review of pricing strategies and structures could help to ensure they are competitive and provide value to customers.
