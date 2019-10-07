# mL-01-linear-regreassion-single


1. IN this project i have created a linear regression model to predict the salary of a given person depending upon their age experiences.
2. I had the option of using scikit learn but i always wanted to do it from scratch.

3. The first step in any machine learning model is to prepare data. pandas is the library which grants us immense power when it comes to data preprocessing and data divison.

4. Using sample method i have shuffled the data set, iloc method is used to create separate test and train data. 
5. So i have devided the program in 4 parts one is the pilot part and other are four methods.
6. Costfun() this is made to calculate the error function j for given t_1,t_0.
7. grad1 is function made to calculate the gradient wrt t_1 and similiarly grad_0 is made for t_0

## Gradient Descent
``` In this Gradient Descent algorithm is used in order to update the theta variables.
 theta = theta - learning_rate * grad(theta)  
 this is how theta is updated. 
 ```
 

FUTURE SCOPE and CURRENT SHORT COMINGS

this code is bit incomplete although its predicting efficiently but we had very clean and short data and only one feature
as more features and train set increases we will need to adopt mini batching or schotohastic linear regression 

DO check out this project and try to make your own code 

Chears have a good one
