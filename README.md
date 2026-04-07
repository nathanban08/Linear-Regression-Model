# Linear-Regression-Model
This project explores how machine learning can be used to train and fit a model to learn from data points and adjust values to create a linear regression line fit to the data.

Linear Regression is a machine learning algorithm that learns from existing data points to model the linear relationship between continuous dependent variables and multiple independent variables (the predictors).

To create a linear regression model from scratch, I started by implementing numpy and madplotlib libraries into a Jupyter Notebook project, and then creating test data points of 100 x and y values. I then used a normal curve to model the slope and y-intercept variables and created a for loop with 1000 iterations of a 0.1 learning rate to train the linear regression model. In order to properly train the model, I implemented gradient descent variables that take the derivative of the mean squared error, and adjusted the model's guess for the slope and y-intercept by the product of the gradient and learning rate of the model. I then printed a progress update of the linear regression model every 100 epochs for the 1000 iterations, finally landing upon a value for the slope and y-intercept that is as close to a perfect line-of-best-fit to the data points as possible. 

I built this model to re-familiarize myself with Jupyter Notebook after a long time of not using the platform, and to create a small, fun project.
