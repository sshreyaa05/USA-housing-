# USA-housing-
## PROBLEM STATEMENT :
Predicting the USA housing prices using ensemble regression techniques can provide valuable insights into the real estate market and has various implications.
## WHY DOES THIS PROBLEM IS VERY REQUIRED TO SOLVE?
Several reasons contribute to the urgency of this problem :
## 1. Affordibility Crisis - there are many people who are not into that economic condition to afford the house for their family and children.
## 2. Homelessness - Lack of affordable housing, along with the combination of economic issues, has led to visible homeless population.
## 3. Social stability - Unstable housing situations can lead to stress, disruptions to their family, hence affecting the overall fabric of the society.
## NOW WE ARE FOCUSSING HOW TO SOLVE THIS PROBLEM LEVERAGING ENSEMBLE LEARNING TO GET A ROBUST MODEL WITH ACCURATE PREDICTIONS :
## But before we begin to solve it, lets get the most important meaningful and interactive insights from the raw data we have:
## 1. distribution of the dependent variable Price
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/1e9b546a-fcf8-496c-b172-f41772a3d498)
## it is approximately normally distributed 
## 2. correlation plot
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/759e9650-ab94-47b7-9538-52ed4c1e9e84)
## as we can see that the average income is having a strong positive correlation with the target variable which is price.
## 3. pairplot or scatter plot matrix showing the relationship between the independent variables or features.
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/681bf058-6f7d-4c61-9c6c-367920b7d8be)
## from this visualisation we can get a clear picture of an identity matrix, where the diagonals are displaying the plots of distribution of features itself and the the scatter plots are showing the relationship between two variables.
## Now, lets begin leveraging machine learning algorithms to solve this problem:
## now, I have employed 3 models, the very first one is linear regression model that shows the residual distribution after training and testing
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/4cd68c90-a5fd-4537-84c3-1383a971b1d1)
## as we can see that it is approximately normally distributed.
## now, the second model, which is random forest regressor showing the residual distribution
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/d2dc5c1d-a330-4c59-ad31-e6bebaca759a)
## as we can see here, that it is slightly left skewed, not approximately normal distribution.
## lastly, the xgboost regressor displaying the residual error
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/8ce5c658-dad9-4c49-b39c-d52e64701a99)
## here, we can see that it is not approximately normal distribution, it is slightly right skewed.
## hence, we come up with the best fitted model or the best model for predicting the price accurately, which is the linear regression with the highest r2-score of 
## 0.9176 and with the lowest rmse value of 102278.82 among all the 3 models.
## the top 4 features influencing the price are:
![image](https://github.com/sshreyaa05/USA-housing-/assets/132264752/b3da1b03-2a1c-4b81-8ae6-45c6f2057d1b)
##  TOP 4 FEATURES THAT ARE INFLUENCING FOR THE PRICE PREDICTION ARE:
## INCOME
## AGE OF THE HOUSE
## NUMBER OF ROOMS
## POPULATION.
