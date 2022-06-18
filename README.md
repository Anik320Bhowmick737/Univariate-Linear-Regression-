# Univariate-Linear-Regression
In this repo I disussed about the project in which I performed a simple linear regression on a dataset "Salary vs Year of experience" using three methods Grdient Descent, Normal equation and Scikit learn package.

## Gradient Descent
Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function. This method is commonly used in machine learning (ML) and deep learning(DL) to minimise a cost/loss function (e.g. in a linear regression (Setting a best fit  line)). 
Cost Function :

$J(\theta)=\frac{1}{2m}\sum(\theta_{0}+\theta_{1}x^{(i)}-y)^2$ 

Where m is number of examples in the feature 
$x^{(i)}$. 
Since ours is a simple univariate linear regression so we have two parameters 
$\theta_{0}$ 
and 
$\theta_{1}$. 
The cost function is minimised by finding suitable values of 
$\theta_{0}$ and $\theta_{1}$.
The iteration rule:

$\theta_{0}=\theta_{0}-\alpha\sum(\theta_{0}+\theta_{1}x^{(i)}-y)$ 

$\theta_{1}=\theta_{1}-\alpha\sum(\theta_{0}+\theta_{1}x^{(i)}-y)x^{(i)}$ 

Result: 

Slope = 9449.962321476278

Intercept = 25792.200198525225

The following is the best fit and scattered plot. 

![Best fit and scatter](https://user-images.githubusercontent.com/97800241/174444691-39dcf5e3-8455-4402-b20c-6db6ed15e81e.png)

Cost vs Iteration:

![Cost vs iter](https://user-images.githubusercontent.com/97800241/174444719-da371d5a-7f91-4d06-b093-d38cbe3dfdda.png)

## Scikit learn Package
using Sklearn almost same result is found.

Slope = 9449.962321455074

Intercept = 25792.20019866871

## Normal Equation
Is based on ordinary least square principle. given y be target and X be feature variable.

$y=X\theta$

$\theta = (X^TX)^{-1}X^Ty$

Result:

Slope = 9449.96232145509

Intercept = 25792.200198668583

