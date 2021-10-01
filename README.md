# Backpropagation
## Session 2 - Backpropagation, embeddings & Language Models
- Rewrite the whole excel sheet showing back-propagation. Explain each major step, and write it on Github.
- Use exactly the same values for all variables as used in the class
- Take a screenshot, and show that screenshot in the readme file
- Excel file must be there for us to cross-check the image shown on readme (no image = no score)
- Explain each major step
- Show what happens to the error graph when you change the learning rate from [0.1, 0.2, 0.5, 0.8, 1.0, 2.0]
- Submit the GitHub link. Github link must be public (check the link without logging in, if it opens, then only share the link as an assignment).

## Excel Sheet Link
- [Backpropagation.xlsx](https://github.com/Aesh-7568/Backpropagation/files/7265463/Backpropagation.xlsx)

## Major Steps involved 
- The algorithm is used to effectively train a neural network through a method called chain rule. In simple terms, after each forward pass through a network, backpropagation performs a backward pass while adjusting the model’s parameters (weights and biases).
- backpropagation aims to minimize the cost function by adjusting network’s weights and biases. The level of adjustment is determined by the gradients of the cost function with respect to those parameters.
- As per the example taken, we have 2 inputs, 2 hidden layer and 2 outputs of our neural network model.Each layer has its own way of working and its own way to take action such that we are able to get the desired results and correlate these scenarios to our conditions.
- The gradient shows how much the parameters needs to change (in positive or negative direction) to minimize E_total.
- Using chain rule we calculate the local gradients.We have learning rate that determines the gradients influence.
- We calculate the change in E_total when we change w1,w2,w3 and w4. Partial derivative is considered and finally termination happens when loss is minimum.

## Screenshots -
### 1. NN Diagram

![BackPropagation](https://user-images.githubusercontent.com/42990724/135494478-49363450-348c-4a14-9f86-ff7552771326.png)

### 2.Loss Chart

![chart](https://user-images.githubusercontent.com/42990724/135494515-c400a432-2e1b-40a7-b344-8689cf31bb2b.png)

### 3. Excel Sheet

![final](https://user-images.githubusercontent.com/42990724/135495255-9562cf63-421e-49f5-a087-edb0ea36b6f3.png)



