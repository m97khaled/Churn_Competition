# Churn_Competition
Context
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]

DATASET CONTENT
Each row represents a customer, each column contains the customer’s attributes described on the column Metadata.

The data set includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents
Inspiration
To explore this type of model and learn more about the subject.

Project approach:
First of all, I preprocessed the IBM dataset sample in the data cleaning stage. 
Furthermore, I started analyzing the dataset to find patterns and understand the data at hand.
Visualization was the key, to derive my insight on the data, I visualized the important features I found to be of value to help in the feature engineering stage.
Finally, I applied a couple of ML models and compared their accuracy in predicting whether a customer would churn or not by feeding the scaled data.
xgboost had the highest accuracy with almost 83% correct predictions. 
