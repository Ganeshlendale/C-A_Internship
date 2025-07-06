# C-A_Internship
This repo mainly aims to my work toward my capstone project offered in internship period.
I have been alloted with combined dataframe with data of about 14 parking parks ans so i categorized data in 14 categories based on the parking park and then cleaned and organised it.
Based on undestanding of dtaframe of each parking park I am curated to understand it and so I worked on it and made an column as "occupancy rate","peak hours" and which are been more responsible for fluctuation of price for parking.
So, i came up with various new columns along with removing unimportant or less preferred columns such as the "id","Time strap"and framed an updated dataframe and so worked for each parking park.
By using the linear regression technique to make the model of Model 1: Baseline Linear Model,and Ridge and Lasso model ti find the preferrd factor and their importance in predicting price and to get  the function,as we get different function for each and every dataframe.And predicted pice for all parking parks.

Files:
1] Ideal_C&A_05.ipynb:THis file depicts the how we trained for each parking area to predict  the price as of by feature selection by "Lasso Technique" nad much more.
2] prediction.ipynb:In this w trained the model based on price output of by model 1 and model 2 and here we came to know Random forest has a lead against other model                      as due to Low MSE and High R^2 and we preferred it and made an model which is also saved for use the public.
3]Final.csv:It contains the predicted price for all parking locations basen on model1 and model 2 as definrd in problem statement.
4]random_forest_price_model.pkl:It is trained model on Random forest as it  is prefereed over other techniques,due to its R^2 and MSE value .
