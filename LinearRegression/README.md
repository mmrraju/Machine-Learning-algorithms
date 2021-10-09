# Linear Regression

In the most simple words, Linear Regression is the supervised Machine Learning model in which the model finds the best fit linear line between 
the independent and dependent variable i.e it finds the linear relationship between the dependent and independent variable.
Linear Regression is of two types: Simple and Multiple. Simple Linear Regression is where only one independent variable is present and 
the model has to find the linear relationship of it with the dependent variable.

Equation of Simple Linear Regression, where c is the intercept, m is coefficient or slope, x is the independent variable and y is the dependent variable.

``` y = c + m*x ```

Equation of Multiple Linear Regression, where c is the intercept, m1,m2,m3,m4…,mn are coefficients or slopes of the independent variables x1,x2,x3,x4…,xn and
y is the dependent variable.

``` y = c + m1*x1 + m2*x2 + m3*x3... +mn*xn ```

A Linear Regression model’s main aim is to find the best fit linear line and the optimal values of intercept and coefficients such that the error is minimized.
Error is the difference between the actual value and Predicted value and the goal is to reduce this difference.
### Numerical Analysis Approach Linear Regression 

### Gradient Descent Approach Linear Regression
The main motivation of this approach is that we reduce error by updating the value of m (slop) and c (intercpt of Y-axis). 
Some optimizers of Gradient Descent are Bold Driver, Adam, Adamax, Adagard, RMSProp etc...
> Batch Gradient Descent
> > Batch Gradient Descent: For updating slop m and intercept of Y-axis c. We use all training data and calculating errors on this training data. This is known as Batch Gradient Descent.

> Stochastic Gradient Descent
> > For updating slop m and intercept of Y-axis c. We don't use all training data except those training data are regarded with m and c.

### Advantage
1. Linear regression performs exceptionally well for linearly separable data.
2. Easier to implement, interpret and efficient to train.
3. It handles overfitting pretty well using dimensionally reduction techniques, regularization, and cross-validation.
4. One more advantage is the extrapolation beyond a specific data set.

### Disadvantage
1. The assumption of linearity between dependent and independent variables.
2. It is often quite prone to noise and overfitting.
3. Linear regression is quite sensitive to outliers.
4. It is prone to multicollinearity.


### Linear Regression Use
 > Sales Forecasting,
 > Risk Analysis,
 > Housing Applications To predict the prices and other factors,
 > Finance Applications To Predict Stock prices, investment evaluation, etc.
 
The basic idea behind linear regression is to find the relationship between the dependent and independent variables. It is used to get the best fitting line
that would predict the outcome with the least error. We can use linear regression in simple real-life-situations, like predicting the SAT scores with regard 
to the number of hours of study and other decisive factors.

