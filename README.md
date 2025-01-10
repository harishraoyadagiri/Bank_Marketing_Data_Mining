# Bank-Marketing-Data-Mining


Dataset: Bank Marketing
Abstract:
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y).
Data Set Information:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact with the same client was required, to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The data covers the period from May 2008 to November 2010.
The dataset consists of four versions, with varying numbers of examples and inputs:
We will be using the “bank-full.csv” (All Examples, Older Version) 
•	Number of Examples: 41,188 
•	Number of Inputs: 17 
•	Older version with fewer inputs 
Source: http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#



Objective:
This project's main goal is to create a predictive model that can accurately forecast whether a client will sign up for a term deposit or not. 
Business Questions:
"What are the key factors influencing a client's decision to subscribe to a term deposit, and how can we optimize our marketing strategies to increase the subscription rate based on these insights?"
"Which of our past marketing campaigns were most effective, and what can we learn from them to improve future campaigns?"

Attribute Information:
Bank client data:
•	Age (Numeric):      Represents the age of the client. 
•	Job (Categorical): Describes the type of job the client has, with categories such as "admin," "unknown," "unemployed," "management," and more. 
•	Marital (Categorical): Indicates the marital status of the client, with categories "married," "divorced," and "single." Note that "divorced" also includes widowed clients. 
•	Education (Categorical): Represents the education level of the client, with categories like "unknown," "secondary," "primary," and "tertiary." 
•	Default (Binary): Indicates whether the client has credit in default. It's binary, with values "yes" or "no." 
•	Balance (Numeric): This numeric attribute represents the average yearly balance in euros. 
•	Housing (Binary): Describes whether the client has a housing loan. It's binary, with values "yes" or "no." 
•	Loan (Binary): Indicates whether the client has a personal loan. Also binary, with values "yes" or "no." 
Related with the last contact of the current campaign:
•	Contact (Categorical): Represents the communication type used for the last contact with the client. Categories include "unknown," "telephone," and "cellular." 
•	Day (Numeric): The day of the month when the last contact was made. 
•	Month (Categorical): Represents the month of the year when the last contact occurred. It has categories like "jan," "feb," and so on, covering the months. 
•	Duration (Numeric): The duration of the last contact in seconds, a numeric value. 
Other attributes:
•	Campaign (Numeric): Indicates the number of contacts performed during the current campaign for this client. It's a numeric value that includes the last contact. 
•	Pdays (Numeric): The number of days that passed after the client was last contacted from a previous campaign. A value of -1 indicates that the client was not previously contacted. 
•	Previous (Numeric): Stands for the number of contacts performed before the current campaign and for this client. 
•	Poutcome (Categorical): Describes the outcome of the previous marketing campaign. Categories include "unknown," "other," "failure," and "success."

Analysis Plan:
Our analyses will include Data preprocessing, Exploratory Data Analysis, Feature engineering, Model selection, and Performance evaluation. 
To make sure the model works well, its performance will be assessed using several measures, including accuracy, precision, recall, F1-score, and ROC-AUC.
Since we are dealing with binary response variables, we will use the below ML models:
•	Logistic Regression
•	KNN 
•	Decision Tree
•	Random Forest
•	Gradient Boosting Machines (e.g., XGBoost)
Further, we will perform hyperparameter tuning to optimize our models. And summarize findings in a clear, actionable report or presentation. 
We will finally give actionable business implications from this analysis. 

Output variable (desired target):
•	y: has the client subscribed to a term deposit? (binary: 'yes', 'no')



![image](https://github.com/user-attachments/assets/214989d5-9bc8-4b9f-9cf8-12c729708e82)
