# Bank Marketing Dataset Visualization on Tableau

## Introduction
The data is related with direct marketing campaigns of a Portuguese banking institution. The bank is trying to market its product through tele-calling. 
The product being marketed by the bank is their Term Deposit, which is our target variable containing 'yes' or ‘no’.
Often, more than one contact to the same client was required, in order to access if the product (bank term deposit)
Data Source: https://archive.ics.uci.edu/ml/datasets/bank+marketing

## Buiness Objectives

1) Exploring patterns and anomalies in the calling patterns, how distributed are the marketing efforts towards wide section of the customers

2) We are interested in knowing how the marketing efforts are translating to results. Quantification of results through visuals would make the business aware of how the marketing efforts are resulting

3) Suggest scope of improvements in the marketing campaigns based on the outcomes of the efforts. Make suggestions based on various attributes of the data available.


#### Data Source: https://archive.ics.uci.edu/ml/datasets/bank+marketing

#### Find fully interactive dashboard at: https://public.tableau.com/views/BankMarketingFinal/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link




## Calling activity distribution across various job roles of customers

![image](https://user-images.githubusercontent.com/98545133/198093449-29b62afb-5261-45f9-977d-ec5413a08017.png)

### Plot Summary:
We are plotting frequency of calls made to customers based on their professions. Additionally, we have color attributed the average duration of calls made to each profession. 

### Observation:
Blue-collared customers are called more often but retired and unemployed customers have higher call duration


## Call frequency distribution across months

![image](https://user-images.githubusercontent.com/98545133/198093641-10057e7e-de34-4f9f-a0de-07c94e59cdf7.png)

### Plot Summary:
We are plotting frequency of average number of calls made to customers based during different months of the year. We have plotted an yearly average of 2.38 calls per customers during the year

### Observation:
May-Aug months witness above average number of calls made to customers, with August having highest count among all months.


## Call frequency distribution across months

![image](https://user-images.githubusercontent.com/98545133/198093784-066a0d6b-26dd-42cb-822c-3417374d7cf8.png)

### Plot Summary:
We are plotting age and marital status distribution of the customers. This is an important demographic attribute for the analysis.

### Observation:
We observe a close to normal distribution in terms of age with major customers in 30 to 40 age group. As the age goes up from 20, married composition increases.

## Dashboarding: Putting it all together

![image](https://user-images.githubusercontent.com/98545133/198093979-2421cde9-8df3-4549-abbe-c7bc15d1606a.png)


### Plot Summary:
We have complied all charts related to demographics and marketing activity data available. We have visualized the target variable ‘Subscribed’ to show the interaction of variables how the target variable changes.
It enables us to understand how each variable influences the subscription to the term deposit by a customer.
