### Term_DepositSubscription_Project

## Project Description
***

Banking is a personalized service-oriented industry that provides services according to the customers’ needs. In our project we are focusing on specific banking service – term deposits.Portuguese bank conducted a marketing campaign using 'telemarketing'. Contact of the client was required, to access if the bank term deposit would be subscribed or not subscribed. To make the upcoming marketing campaign more effective the Portuguese bank wants to identify which type of customers is more likely to make term deposits and focus marketing efforts on those customers.This will not only allow the bank to secure deposits more effectively but also increase customer satisfaction by reducing undesirable advertisements for non-potential customers. The objective of our application is to identify the potential customers that subscribe for term deposits. Our application analyses customer features, such as demographics and transaction history, the bank will be able to predict customer saving behaviors and identify which type of customers is more likely to make term deposits.
  
  
## Use case Description
***
# Usecase name : Term deposit subscription prediction

#Actors : Bank Data Analyst(s)

#Precondition : Data Analyst has access to run the application.                 

#Description: This use case allows analyst to predict the potential customers for subscription of term deposit.
Use case begins with user entering path to csv data file as input for the application. 
The application builds classification model that predicts the list of potential customers. 
List of potential customers for subscription of term deposit is generated for future campaign usage. 

#Postcondition: Analyst gets list of potential customers for subscription of term deposit


## Useful features from the data & the descriptions of the features
***

 age : customer age (numeric)
 
 job : type of job (type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
 
 marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
 
 education : education level (categorical: "unknown","secondary","primary","tertiary")
 
 default : has credit in default? (binary: "yes","no")
 
 balance : balance level (numeric) 
 
 housing : has housing loan?(binary: "yes","no") 
 
 loan : has personal loan? (binary: "yes","no")
 
 contact : contact communication type  (categorical: "unknown","telephone","cellular") 
 
 day : last contact day of the week (numeric)
 
 month : last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
 
 duration : last contact duration, in seconds (numeric)
 
 campaign : number of contacts performed during this campaign and for this client (numeric)
 
 pdays : number of days that passed by after the client was last contacted from a previous campaign(numeric) 
 
 previous : number of contacts performed before this campaign and for this client (numeric)
 
 poutcome : outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
 
 y : has the client subscribed a term deposit? (binary: "yes","no")


## Data Source
***

The data file used in the project is bank-full.csv
https://data.world/uci/bank-marketing
https://www.kaggle.com/yufengsui/portuguese-bank-marketing-data-set?select=bank-full.csv
https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
