## Calculas in AI

- Calculas is like finding a minimum loss and updating the weight.
- Start with random weight.
- Model gets the input and makes a prediction.
- And also calculate the loss(Loss tell how wrong the model is based on the weight).
- Repeat it till the loss is minimum
- Sympy(Symbolic Math) library.

## 1. Derivatives

- Using Derivatives, we can changes the weight in a direction to reduce the loss or reduce the error.

![alt text](Images/derivative.png)


## 2. Gradients

- Gradients will tell which direction which direction the loss is increasing and how fast the loss is changing in respect to the weight.

## 3. Gradients Descent

- It is a optimization algorithm.
- Using gradients decent, we can keep on changing the weights in the opposite direction of the gradient until the loss is small.
- we need to go the opposite direction of the gradient to reduce the loss.
- we can calculate the loss is using loss function(MSE: Mean squared error).

![alt text](Images/example1.png)

## 4. Chain Rule

- Chain rule will help us to calculate how a small change in one input  affects the final output,
- one function depends on others..chaining multiple layers.
- Input Layer > Hidden Layer > Output.(Data goes from input through hidden layer to the output)

## 5. Parital Derivatives

- If we have multiple inputs e.g like x,y, we can one variable and we can measures how change in one variables and affect the result.

![alt text](Images/pd.png)

## 6. Backpropagation

- First it makes prediction.
- Then it see how wrong the model was(error/loss) and see what is the loss
- Then it goes backward with the help of chain rule and calculate how each layer contributed to the error.
- And it adjusts the weight  to reduce the error and try to predicte it again.
- Learn from the mistakes.

**Forward Pass :** Input goes through the network - get the output.
**Calculate Error :** Calculate the Loss.
**Backward Pass :** Calculate how each contributed to the loss and adjust the weight again.


## 7. Bias 

- Bias helps the model to make prediction when the input is zero.
- Imagine we are predicitng a house price prediction, equation : ouput = w * x
- If x input is 0, prediction is 0.
- With bias we can add a fix base value for the house, equation: w * x + b
- if input is 0, b=10000(fixed value we are setting).

## 7. Activation

- using relu, we can check for the positive value.If it is there it will return orelse if it is negative we return 0
