# Telco-Customer-Churn
Be free to see the full version of jupyter notebook via link:
https://nbviewer.jupyter.org/github/Cindy1122334455/Telco-Customer-Churn/blob/master/Telco-Customer-Churn.ipynb

## Data Overview
The data was downloaded from IBM Sample Data Sets for customer retention programs. The objective of this project is to predict behaviors of churn or not churn to help retain customers. Each row represents a customer, each column contains a customer’s attribute.
This dataset contains only 7043 rows, 21 columns and only 11 missing values.

The data set includes information about:
*     Customers who left within the last month – the column is called Churn
*     Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
*     Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
*     Demographic info about customers – gender, age range, and if they have partners and dependents

## Findings & Insights 
* customers who did not sign up for any Online services are churning with least percentage and customers who signed up for only one Online Service are churning with the highest percentage.
* Customers who does not use any internet service are paying just 33 dollars, while those who with one service are paying double which is 66 dollars. As the number of services used increases, the Average Monthly Charges are increasing linearly.
* The higher the monthly charges, the more is the possibility of Churning. Customers who are not churnig are paying over 60 dolars, while customets who are churning are paying about 80 dollars.
* Over 60% of customers who churn in one month and the churn probability reduces to about 25% at the end of 24 months.
* Customers with Month-to-Month contract are churning most with 88.6%, while customers with two-year contract are churning with only 2.57%.
* The percentage of non-churning customers among 4 types of payment method are almost the same. However, customers who use Electronic Check as payment method are churning most in the right hand side plot.
* Customers without MultipleLines(including no phone service) are churing in higher proportion.
* Customers who are using Streaming Movies and StreamingTV are churning in higher proportions.
* Customers with Fiber Optic internet service are churning in the most proportion with 69.4%.
