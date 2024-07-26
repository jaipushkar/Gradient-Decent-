# Gradient-Decent-

**Gradient Descent Linear Regression**
This script demonstrates the implementation of gradient descent for simple linear regression. The goal is to fit a line to the data points that minimizes the mean squared error (MSE) between the predicted values and the actual values.

**How It Works**
**Initialize Parameters:** Start with initial guesses for the slope (m_curr) and the intercept (b_curr) of the line.
**Calculate Predictions:** Use the current values of m_curr and b_curr to make predictions (y_predicted) for the target variable.
**Compute Cost:** Calculate the mean squared error (MSE) between the actual values (y) and the predicted values (y_predicted).
**Update Parameters:** Adjust m_curr and b_curr using the gradients of the cost function with respect to these parameters. The learning rate controls the size of these adjustments.
**Iterate:** Repeat steps 2-4 for a specified number of iterations to converge to the optimal values of m_curr and b_curr.
