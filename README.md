# project-2

# The Bank Customer Churn Prediction

[The dataset of this project is for the Bank Customer Churn Prediction](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset) 

The task is to predict whether a bank customer will 'churn' or close their account. I think there has strong correlation between the target and the columns of Balance and Age

For the Churn vs Balance plot, it tells that Customer Churn has less average balance than who does not Customer Churn. This might be affected to the bank if they close their accounts. Therefore, the bank need to find a way to hold those Customer Churn.

For the Churn vs Age plot, it tells that the average age of the Customer Chun is lower than the average age of the Customer Chun. I think some people close the account when they are approximately 35. Therefore, the bank need to focus on making new customers.
![Churn vs Balance and Churn vs Age](https://user-images.githubusercontent.com/109550293/193689333-fae36f55-0eab-4a0a-9f7c-b15a2daed6ce.png)


Test different model with Training and Testing :

  1.KNN model
  
  2.KNN model with the GridSearchCV
  
  3.Random Forest
  
  4.Random Forest with the GridSearchCV
  
In my recommendation, 

- The KNN with the GridSearchCV model will be the best because there has less errors when I compared with other confusion matrixes. 
  
- Confusion matrix for the KNN with the GridSearchCV shows 46 errors in the total, but other confusion matrix shows more error than KNN with the GridSearchCV. 

- True Negative is better than True Positive at predicting in the confusion matrix for the KNN with the GridSearchCV

![The KNN model with the GridSearchCV](https://user-images.githubusercontent.com/109550293/193691424-f6389212-b2eb-49e9-a577-b2b52b862358.png)

Rcommendation for the Bank: 
These are cases in which we predicted that there has a lot of Churn Customers. I will recommend to find new customers as many as you can since there has a lot of Churn Customers in the bank.



