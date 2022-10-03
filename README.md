# project-2

[The dataset of this project is for the Bank Customer Churn Prediction](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset) 

The task is to predict whether a bank customer will 'churn' or close their account. I think there has strong correlation between the target and the columns of Balance and Age

For the Churn vs Balance plot, it tells that Customer Churn has more average balance than who does not Customer Churn. This might be affected to the bank if they close their accounts. Therefore, the bank need to find a way to hold those Customer Churn.

For the Churn vs Age plot, it tells that the average age of the Customer Chun is higher than the average age of the Customer Chun. I think some people close the account when they are approximately 40. Therefore, the bank need to focus on making new customers.
![Churn vs Balance and Churn vs Age](https://user-images.githubusercontent.com/109550293/193681443-5ae5934c-9bba-487e-8d1e-a26a288427e7.png)


Test different model with Training and Testing :

  1.KNN model
  
  2.KNN model with the GridSearchCV
  
  3.Random Forest
  
  4.Random Forest with the GridSearchCV
  
In my recommendation, 
![The KNN model with the GridSearchCV](https://user-images.githubusercontent.com/109550293/193681750-449c2be2-b630-4f7d-8efb-994f3fb9e553.png)
- The KNN with the GridSearchCV model will be the best because there has less errors when I compared with other confusion matrixes. 
  
- Confusion matrix for the KNN with the GridSearchCV shows 56 errors in the total, but other confusion matrix shows more error than KNN with the GridSearchCV. 

- True Negative is better than True Positive at predicting in the confusion matrix for the KNN with the GridSearchCV

