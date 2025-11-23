# Linear-Regression-SageMaker-Linear-Learner
A Linear Regression model that could accurately predict employee salary based on number of years of experience. </br>
</br>
Linear Regression Intuition: In Simple Linear Regression, we predict the value of one variable Y based on another vairable X. X is called the independent vairable and Y is called the dependent variable. When the independent variable increases (or decreses), the dependent variable increses (or decreses) in a linear fashion.   

### Training Dataset Workflow:
<img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/11ae30bd-9481-4437-89f8-3c2322514c28" />

### Expected Linear Regression Plot: 
<img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/1dca7649-83eb-408c-a079-9615cd6443d7" /> 
</br> We'll put the data points and our objective will be to come up with a linear straight line. Goal is to obtain a relationship b/w employee salary and number of years of experience.

```bash
  y=mx+b                  //where "m" is the slope of graph, "b" is the y-intercept and x, y are cordinates.
```
Once the coefficients "m" and "b" are recieved, we have obtained a simple linear regression model. If "b" is zero, the line passed through the Origin. eg: y=3*x </br>
If m(slope) is positive, x and y are directly proportional to each other and if m(slope) is negative, x and y are inversly proportional to each other. 

### Least Sum of Squares: 
Way to find the best fit curve or line for a set of points. This method is also used to find the coefficients a and b.

</br>
Data set is divided into 75% for training and 25% for testing. </br>
Training set: Used for Model training. </br>
Testing set: Used for testing trained model.

