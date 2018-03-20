# Predicting-House-Price-using-Multiple-regression

[Download data files from here.](https://github.com/gov-vj/Estimating-House-Price-based-on-sqft_living-and-no-of-bedrooms)

Libaries used: numpy, pandas, matplotlib, scikit

Tools used: Jupyter Notebook

I trained 3 different models.

  * model 1: sqft_living(house size), #bedrooms, #bathrooms, latitude, longitude
  * model 2: model 1 features + #bedrooms multiply by #bathrooms
  * model 3: model 2 features + #bedrooms_squared, log(sqft_living), latitude plus longitude

Result: model 1 is underfit and model 3 is overfit.

## 2nd Half (Implementation of linear regression from scratch using gradient descent)

After implementing the linear regression froscratch I have implemented 2 more models.

  * model 1: It is a simple regression using single feature sqft_living. It is the same model as the model 1 from [this project](https://github.com/gov-vj/Implementing-closed-form-solution-for-simple-regression/blob/master/README.md) where I trained the model using LinearRegression object from scikit library.
  
  * model 2: Multiple regression using features: sqft_living, sqft_living15 (average size of nearest 15 houses in sq. ft.)
  
 Result: model 1 coefficient from this project is almost equal to the coefficients from the previous project where I used the scikit library.


[Other Machine Learning Projects](https://github.com/gov-vj/Machine-Learning-Projects)
