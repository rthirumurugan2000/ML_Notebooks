# Predict no of Upvotes

### Dataset: Analytics Vidhya
Help a StackOverflow like platform to identify the best question authors by predicting the upvote count of questions asked.

Crowdsourced online content platforms have a constant need to identify the best content in time to appropriately promote and thereby 
improve the engagement at the website. This challenge involves a similar problem of predicting the upvote count for a queries posted and 
identify the parameters that affect it the most.

### Problem Statement:

An online question and answer platform has hired you as a data scientist to identify the best question authors on the platform
This identification will bring more insight into increasing the user engagement. Given the tag of the question, number of views received,
number of answers, username and reputation of the question author, the problem requires you to predict the upvote count that the question
will receive.

### Data Dictionary
 

#### Variable	        
Definition

#### ID	              
Question ID

#### Tag	            
Anonymised tags representing question category

#### Reputation      	
Reputation score of question author

#### Answers	        
Number of times question has been answered

#### Username	        
Anonymised user id of question author

#### Views	         
Number of times question has been viewed

#### Upvote(Target)  
Number of upvotes for the question

### Evaluation Metric:

The evaluation metric for this competition is RMSE (root mean squared error)

## Analysis:

I carried out exploratory data analysis on the dataset.I have tried running the models through SVM and XGboost,it resulted in 
a very huge RMSE value.Finally,I used Polynomial Regression(LASO),which gave me a decent RMSE value.

#### RMSE VALUE OBTAINED: 
1006.434 (Analytics Vidhya Leaderboard)

### DEVELOPER
#### Thirumurugan Ramar
 



 
