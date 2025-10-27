## Problem statement :
WA telecom wants to capture some Key performance indicators (KPIs) about its customer churn for a month.
It wants to see whether customers are leaving the services or staying with it in a particular month, also look out for what is the customer demographic looks like – Gender, Occupation type, type of services opted..

### Problem description :
- WA telecom is a major telecom player in USA.
- It captures its customer usage data from many sources.
- Retrieving intelligent insights from its data sets is a tedious manual exercise today.
- It is looking for some data engineering assistance to consolidate the data from multiple systems into one object, gather what insights can be derived for Customer Churn for a particular month
- Have few reports build as deliverable. Reports WA telecom is looking for should have : 
- Churn Ratio for a month ( Total Customers vs Customer Churned)
- What kind of occupation its customers have for a region
- How many Senior Citizens are using its services
- What are the different services being used by customers

## Engineering path :

- Set up Python on your laptop to process the data files
- Install and set up a Db (PostGres) to create the final consolidated data object and build SQL reports as per business need
- Consolidate the different data sets into one object
- Apply data transformational logic to derive the required metrices
- Join with Demographics to gain customer distribution as per occupation
- Generate reports for business by applying statistical logic