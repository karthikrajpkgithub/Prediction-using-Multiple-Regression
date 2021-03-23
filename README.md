# Prediction-using-Multiple-Regression

Multiple linear regression is the extension of linear regression in the relationship between more than two variables.In multiple regressions, we have more than one predictor variable and one response variable.

### Formula for multiple regression 

y=b0+b1*x1+b2*x2+b3*x3+⋯bn*xn

> y is a response variable.

> b0, b1, b2...bn are the coefficients.

> x1, x2, ...xn are the predictor variables.

### Dataset used: "mtcars" dataset present in the R environment.

Here we use the "mpg" as a **response variable** with "wt", "disp" and "hp" as **predictor variables.**

### Create a subset of these variables from the "mtcars" dataset.
```
data<-mtcars[c("mpg","wt","disp","hp")]  
```
Description of variables:

mpg: Miles/(US) gallon

disp: Displacement (cu.in.)

hp: Gross horsepower

wt: Weight (1000 lbs)
