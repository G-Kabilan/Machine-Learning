## DETECTING FRAUDULENT TRANSACTIONS- MACHINE LEARNING
## Overview
#### PROBLEM STATEMENT:
Empowering Financial Security fraud is a growing problem, leading to financial losses for businesses and a negative experience for customers. Fraudsters employ various tactics like stolen credit cards, account takeover, and friendly fraud. The goal is to build a classification model that can accurately classify transactions as either legitimate or potentially fraudulent.

#### SOLUTION:
Develop a real-time fraudulent transaction system using machine learning. This model will analyze the customer data, transactional details, and historical patterns to identify the suspicious activity with high accuracy.



### STEPS FOLLWED IN JUPYTER NOTEBOOK (Python)

- Data Collection and Preparation: Gathering and preprocessing     data related to demographics and employment.

- Predictive Modeling: Using machine learning algorithms to   predict fraudulent transaction based on various features.

- Visualization and Reporting: Creating visual representations of the data and results to communicate findings effectively.

### SNAPSHOT OF VISUAL ANALYSIS


![image](https://github.com/G-Kabilan/Machine-Learning/assets/148671435/029dfb58-96f4-452e-aafc-9899de8e747c)

## Observations:

### Account Age Distribution: 
There is a significant peak at 2000 days, indicating a large number of old accounts.
A smaller but notable peak at 0-100 days, indicates new accounts.
Insights:
The presence of many new accounts may be indicative of users creating new accounts frequently, possibly for fraudulent activities.
The older accounts could belong to loyal, long-term users.

### NumItems:
Most transactions involve only 1 item, with very few transactions involving more than 1 item.
Insights:
Single-item transactions dominate, suggesting that users typically buy one item per transaction.
Multiple-item transactions are rare and could be worth examining for unusual patterns or potential fraud.

### Local Time Distribution
Transactions are spread throughout the early hours, with a peak of around 5 hours local time.
Insights:
The distribution suggests a steady stream of transactions with a minor peak in the early morning, which may be influenced by specific user behaviour or time zone differences.

### Payment Method Distribution
Credit cards are the most commonly used payment method, followed by PayPal, with store credit being the least used.
Insights:
The high usage of credit cards indicates a preference or requirement for credit transactions in the dataset.
Store credit's minimal use suggests it is not a popular choice among users.

### Payment Method AgeDays Distribution
A significant number of payment methods are very new, with ages close to 0.
Insights:
The high frequency of new payment methods could be a red flag for fraudulent activities, as fraudsters often use newly created payment methods to avoid detection.

### Is Weekend Distribution
Transactions are nearly evenly split between weekends and weekdays.
Insights:
Fraudulent activity does not appear to be strongly influenced by the day of the week.
Analyzing weekend versus weekday transactions might not yield significant differences in fraud detection.

### Category Count
Transactions are evenly distributed among the three categories: shopping, electronics, and food.

### Day_time Distribution
The majority of transactions occur in the early morning, with a smaller number occurring at night.
Insights:
The time of day could be a useful feature for predicting fraud, as certain times may be more prone to fraudulent activities.

### Is Fraud Distribution
There is a significant imbalance in the dataset, with very few fraudulent transactions compared to non-fraudulent ones.

The high-class imbalance indicates that special techniques (such as SMOTE or adjusting class weights) will be needed during model training to ensure the model can accurately detect fraudulent transactions.


