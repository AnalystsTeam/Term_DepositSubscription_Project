# Term_DepositSubscription_Project

## Project Description
***

Banking is a personalized service-oriented industry that provides services according to the customers’ needs.In our project we are focusing on specific banking service – term deposits.
Portuguese bank conducted a marketing campaign using telemarkrting.Contact of the client was required, to access if the bank termdeposit would be subscribed  or not subscribed. To make the 
upcoming marketing campaign more effectve the Portuguese bank wants to identify which type of customers is more likely to make term deposits and focus marketing efforts on those customers.
This will not only allow the bank to secure deposits more effectively but also increase customer satisfaction by reducing undesirable advertisements for certain customers. 
The objective of our application is to identify the potential customers that subscribe for term deposits. Our application analyses customer features, such as demographics and 
transaction history, the bank will be able to predict customer saving behaviors and identify which type of customers is more likely to make term deposits.
  

## Useful features from the data & the descriptions of the features
***

 age : customer age
 job : type of job
 marital : marital status
 education : education level
 default : has credit in default?
 balance : balance level
 housing : has housing loan?
 loan : has personal loan?
 contact : contact communication type
 day : last contact day of the week
 month : last contact month of year
 duration : last contact duration, in seconds
 campaign : number of contacts performed during this campaign and for this client
 pdays : number of days that passed by after the client was last contacted from a previous campaign
 previous : number of contacts performed before this campaign and for this client
 poutcome : outcome of the previous marketing campaign


## Target
***

 y : has the client subscribed a term deposit?


## Data Source
***

https://www.kaggle.com/yufengsui/portuguese-bank-marketing-data-set?select=bank-full.csv
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing


## Usecase Description
***
# Usecase name : Term deposit subscription prediction

#Actors : Bank Data Analyst(s)

#Precondition : Data Analyst has access to run the application. 
                CVS Data file uploaded has similar data format as our datafile

#Description : This usecase allows analyst to predict the potential customers for subscription of term deposit.
Usecase begins with user uploading the csv data file as input for the application. 
The appliaction builds clasification model that predicts the list of potential customers. 
List of potential customers for subscription of term deposit is generated for future canpaign usage. 


#Postcondition : Analyst gets list of potential customers for subscription of term deposit
