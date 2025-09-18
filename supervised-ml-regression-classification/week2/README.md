# Multiple features

If there are many features, you may have difficult equation to come to linear regression.

## Multiple linear regression

When you have more than one input features, the Linear regression problem is called multiple linear regression.

**Vectorization** is a mechanism that modern data science libraries like Numpy use to parallelize computations over vector datasets. In general sense, if you wanted to perform addition or multiplication on Python list, you would do that in a loop, but with a vectorized operation, you can do that in one line of code where Numpy handles operation on each item in the array in parallel fashion.


- [Lab 1: Python Numpy Vectorization](./Lab01_Python_Numpy_Vectorization_Soln.html)
- [Lab 2: Multiple Linear Regression](./Lab02_Multiple_Variable_Soln.html)
- [Practice Quiz: Multiple Linear Regression](quiz1.html)

Sometimes, features are not in the same scale. In this case, your model might come up with different sets of weights for these set of features. If the features are not in the same scale, you can normalize them by subtracting the mean and dividing by the standard deviation. This is called **feature scaling**. Feature scaling can lead to quicker convergence to the optimal model parameters. This can lead to quicker convergence to global minima in the cost function for Gradient descent.

- [Lab 3: Feature Scaling and Learning Rate](./Lab03_Feature_Scaling_and_Learning_Rate_Soln.html)

Choosing correct features can impact your model in a big way. If you have features for length and width of a house, you could combine them into single feature as area. Feature engineering requires domain knowledge of the problem.

- [Feature Engineering and Polynomial Regression](./Lab04_FeatEng_PolyReg_Soln.html)

- [Practice Quiz: Gradient Descent in Practice](quiz2.html)

- [Assignment 1: Linear Regression](./Assignment1_Linear_Regression.html)