# Predict-Responses-to-Marketing-Campaign-
in this project we trained machine learning models using Customers' data set to predict which customer is worth spending the marketing effort on. This is a classification problem that aims to classify each customer as (will respond, will not respond) based on their personal data, demographics, buying habits, and how they acted to previous campaigns.
# Data-set
This data-set from Kaggle contains information of 2240 customers with 29 columns including demographics, buying habits, and how they acted to previous campaigns, here are the features:
1-	ID: Unique identification code for each customer
2-	Year_Birth: The DOB Year of the customer
3-	Education: Customer’s level of education.
4-	Marital_Status: Customer’s status of Marriage
5-	Income: Customer’s  annual Income
6-	Kidhome: Number of children under 13 in Customer's house
7-	Teenhome: Number of children between 13-19 in Customer's house
8-	Dt_Customer: Date of customers enrollment
9-	Recency: Number of days since last purchase
10-	MntWines: the amount of money spent on Wines in the last 2 years.
11-	MntFruits: the amount of money spent on Fruits in the last 2 years.
12-	MntMeatProducts: the amount of money spent on Meat products in the last 2 years.
13-	MntFishProducts: the amount of money spent on Fish products in the last 2 years.
14-	MntSweetProducts: the amount of money spent on Sweet products in the last 2 years.
15-	MntGoldProds: Dollar the amount of money spent on Gold products in the last 2 years.
16-	NumDealsPurchases: Number of purchases made with a discount.
17-	NumWebPurchases: Number of purchases made through the company's website.
18-	NumCatalogPurchases: Number of purchases made using the catalog.
19-	NumStorePurchases: Number of purchases made directly in-store.
20-	NumWebVisitsMonth: Number of visits made through the company's website.
21-	AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise.
22-	AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise.
23-	AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise.
24-	AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise.
25-	AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise.
26-	Complain: 1 if the customer complained in the last 2 years, 0 otherwise.
27-	Response: 1 if customer accepted the offer in the last campaign, 0 otherwise.
28-	Z_CostContact cost spent on this customer ( for marketing).
29-	Z_Revenue revenue gained from this customer.
Data-set link: https://www.kaggle.com/rodsaldanha/arketing-campaign

# Libraries
We used Python 3.6 in this project. and need the following libraries:
•	numpy
•	pandas
•	seaborn
•	matplotlib
•	collections
•	imblearn 
•	sklearn
•	datetime
