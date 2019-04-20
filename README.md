# Top-10-Artificial-Intelligence-Algorithms
<h1> <strong> ......................................... (1) ..... ..........................................</strong></h1>

# Linear Classification

####  What is Classification?
Classification is the process of predicting the class of given data points. Classes are sometimes called as targets/ labels or categories.
Classification predictive modeling is the task of approximating a mapping function (f) from input variables (X) to discrete output variables (y).

#### Linear Classification 

Linear Classificaiton is used for finding linear relationship between target(Y) and input variables(X).



####  Y(pred) = b0 + b1*x

The values b0 and b1 must be chosen so that they minimize the error. If sum of squared error is taken as a metric to evaluate the model, then goal to obtain a line that best reduces the error.

Something like this 

#### Hypothesis function for Linear Regression 

![alt text](https://cdn-images-1.medium.com/max/800/1*Utp8sgyLk7H39qOQY9pf1A.png)

### How function finds the best fit model
While training the model we are given :

- X: input training data
- Y: labels to data (supervised learning)

When training the model – it fits the best line to predict the value of y for a given value of x. The model gets the best regression fit line by finding the best θ1 and θ2 values.

- b0: intercept
- b1: coefficient of x



Once we find the best b0 and b1 values, we get the best fit line. So when we are finally using our model for prediction, it will predict the value of y for the input value of x.
- For finding the best fit line in response to the suitable value of b0 and b1 <b> The  Gradient Descent method is used </b>

###  How the Linear Classification algorithm is practically used 
To Demonstrate how linear classification is is practically used go through the ipython notebook. In the noteobook using kaggle Titanic competition  passenger data and predicting the survial of the passenger.

## [Linear-Classification](https://github.com/AIVenture0/Top-10-Artificial-Intelligence-Algorithms/blob/master/Linear%20Classification/Linear_classification_with_titanic_data.ipynb)
