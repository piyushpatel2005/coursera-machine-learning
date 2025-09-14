# Intro to Machine Learning

## Supervised Learning

- 99% of values created by ML.
- supervised learning refers to learn from input to output mapping. 
- give learning algo examples that learn from right answers based on labels.
- it's by seeing correct input x and output y.

- [Lab 1: Python Jupyter](./Lab01_Python_Jupyter_Soln.ipynb)
- [Practice Quiz](quiz1.html)

### 1. Regression

- predict number from many possible numbers. For example, house price prediction

Univariate linear regression is one input feature linear regression.
If there are more than on3 features

- [Lab 2: Model Representation](./Lab02_Model_Representation_Soln.ipynb)
- [Lab 3: Cost Function](./Lab03_Cost_Function_Soln.ipynb)
- [Practice Quiz: Regression](quiz2.html)

#### Gradient descent

On each step update the parameter by calculating slope. Learnings rate is the rate which determines the step taken to reach the optimal minima.

Gradient Descent depends on Learning rate. If learning rate is too large, it may overshoot local minima and if it's too small, it may slowly converge to the minima.

- [Lab 4 Gradient Descent](./Lab04_Gradient_Descent_Soln.ipynb)
- [Practice Quiz: Train the model with gradient descent](quiz3.html)


### 2. Classification

- trying to categorize data instead of finding number from many possible options
- small finite numbr of possible output categories (classes)
- spam detection
- breast cancer detection

## Unsupervised Learning

- In this case data is not associated with any output label y.
- find some pattern or structure around data
- data can be grouped into some clusters
- data comes with inputs x but not output labels y. Algorithm has to find structure in the data.

### Clustering Algorithm

- group data into multiple clusters
- grouping news stories or recommendation

### Anomaly Detection
- used to detect unusual data points such as fraud detection

### Dimensionality Reduction

- compress big data set to smaller dataset.

## Terminologies

- Training set: dataset used to train the model.
- Feature: Input values like `x` like size in square feet. 
- Target: this is the output you want to predict `y` like house of price.
- Parameters: Parameters are machine learning function coefficients. They are also called weight. This are adjusted during model training to reach optimal function.
- Cost function: is the function used to determine the best algorithm. The goal is to minimize the cost function.