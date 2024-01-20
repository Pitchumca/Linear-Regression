Load the Dataset To check for the assumptions of linear regression, such as linearity, homoscedasticity, independence, and normality, we can use several methods and visualizations. Here's how we can approach each one using Python:

Linearity: This can be checked with a scatter plot of observed vs. predicted values or independent vs. dependent variables.

Homoscedasticity: This refers to the assumption that the residuals (differences between observed and predicted values) have constant variance at all levels of the independent variable(s). We can visualize this using a scatter plot of residuals vs. predicted values or independent variables.

Independence: This is the assumption that the residuals are independent of each other. This is more of an experimental design issue, but Durbin-Watson statistics can be used to test for autocorrelation in the residuals.

Normality: The assumption that the residuals are normally distributed can be checked with a Q-Q plot or a histogram.

