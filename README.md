# bhuvi_bank_project
 Project Title : Predicting the effectiveness of bank marketing campaigns.
 
Problem Statement : The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe a term deposit (variable y). The dataset consists of direct marketing campaigns data of a banking institution which consisted of 45211 data points with 17 independent variables out of which 7 were numeric features and 10 were categorical features


Approach 

Performed exploratory data analysis with to get insights from the data to observe following things:-

The dataset was imbalanced, where the number of negative classes is close to 8 times the number of positive classes. The customers who had a job of admin had the highest rate of subscribing a term deposit, but they were also the highest when it comes to not subscribing. This is simply because we have more customers working as admin than any other profession. Majority of the customers were married. Followed by Single, divorced and unknown. Majority of the customers had a housing loan.

Models Implementation:-

Logistic Regression

Logistic Regression(under sampling)

Random Forest(under sampling)

Random Forest(under sampling)

K-NN(over sampling)

XGBoost(over sampling)

Conclusion:-

Random Forest and XGBoost have shown the best performance with a Test AUC-ROC of 0.93 and 0.91.
The customer's account balance has a huge influence on the campaign's outcome. So we can address those customers having good account balance .
The customer's age affects campaign outcome as well.
Number of contacts with the customer during the campaign is also crucial.
Outcome of previous marketing campaign also plays an important role. So we can focus on previous customers more in order to increase success of the campaign.
